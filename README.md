# aula2_arquiteturaDeSoftware

### 1. Quais são as principais desvantagens de concentrar toda a lógica, interface e dados em um único arquivo?

- **Manutenção complicada**: Conforme o código vai crescendo, fica uma bagunça e muito mais difícil de entender ou alterar.
- **Reaproveitamento de código**: Sem separação, é difícil reutilizar funcionalidades em outros projetos ou partes do sistema.
- **Escalabilidade ruim**: Pequenas mudanças podem causar problemas em várias partes do sistema.
- **Testes complicados**: Testar funcionalidades específicas fica difícil, já que está tudo junto.
- **Trabalho em equipe**: Quando várias pessoas mexem no mesmo arquivo, os conflitos de código são frequentes.

---

### 2. Como a separação em camadas facilita a manutenção e a escalabilidade da aplicação?

- **Organização melhor**: O código fica mais limpo e fácil de entender, com cada parte (interface, lógica, dados) bem definida.
- **Manutenção tranquila**: Dá pra alterar uma parte do sistema sem causar problemas em outras.
- **Reutilização de componentes**: Funções e regras podem ser reaproveitadas em outros lugares.
- **Testes mais fáceis**: Cada camada pode ser testada isoladamente.
- **Escalabilidade e colaboração**: É mais fácil escalar e times diferentes podem trabalhar em partes específicas sem pisar no código dos outros.

---

### 3. Quais são os principais benefícios da arquitetura Pipe e Filtros para sistemas que precisam de flexibilidade nas transformações de dados?

- **Modularidade**: Cada filtro é uma função independente, fácil de adicionar ou remover.
- **Flexibilidade**: Os filtros podem ser combinados e rearranjados conforme necessário.
- **Reutilização**: Filtros podem ser usados em diferentes partes do sistema.
- **Fácil manutenção**: Novos filtros podem ser criados e encaixados na sequência sem quebrar o sistema.
- **Testes isolados**: Dá pra testar cada filtro separadamente, facilitando a identificação de problemas.
