# aula2_arquiteturaDeSoftware

# Aplicação Monolítica vs Arquiteturas em Camadas e Pipe e Filtros

## Desvantagens de Concentrar Tudo em um Arquivo

- **Manutenção complicada**: Quando o código cresce, fica bagunçado e super difícil de entender e mexer depois.
- **Nada de reutilizar código**: Como tá tudo misturado, você acaba duplicando código em vez de reaproveitar.
- **Escalabilidade? Quase zero**: Qualquer mudança, mesmo pequena, pode quebrar tudo.
- **Testes são um pesadelo**: Testar uma parte do código sem interferir em outra é quase impossível.
- **Trabalho em equipe? Nem rola**: Todo mundo mexendo no mesmo arquivo gera conflito o tempo todo.

## Por que Separar em Camadas?

- **Organização top**: Tudo fica mais claro e organizado, cada parte tem sua função.
- **Manutenção fácil**: Mudar uma parte da aplicação sem mexer em outra é super tranquilo.
- **Reaproveitamento de código**: Dá pra reutilizar a lógica de uma camada em várias partes.
- **Testes mais tranquilos**: Como cada camada é separada, dá pra testar tudo de boa.
- **Facilita o crescimento**: Dá pra escalar e melhorar o sistema sem medo, e várias pessoas podem trabalhar juntas numa boa.

## Benefícios da Arquitetura Pipe e Filtros

- **Modularidade**: Cada filtro faz só uma coisa, e você pode trocar ou adicionar novos filtros fácil, fácil.
- **Flexibilidade máxima**: Dá pra combinar e rearranjar os filtros do jeito que quiser.
- **Reutilização dos filtros**: Um filtro que remove espaços pode ser usado em várias partes do sistema.
- **Manutenção de boa**: Precisa de uma nova transformação? Só criar mais um filtro e pronto.
- **Testabilidade**: Testar um filtro por vez deixa o sistema mais confiável e menos propenso a bugs.
