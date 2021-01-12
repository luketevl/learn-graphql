# Links
- https://www.howtographql.com/
## Slides
- https://docs.google.com/presentation/d/1QctAckhGlvs0NMgf_GsRdqui_cm0UqJOew55WFChjNg/edit?usp=sharing
# Clients
## Fetch Client
> Muito simples apenas busca os dados.

## Caching Client
> Busca os dados, transforma e adiciona em cache.

### Exemplos
- FetchQL
  - Vantagens
    - Bastante leve
    - API simplificada
    - Escrito em ES2015 e modules
    - **Isomórfico**
  - Desvantagens
    - Não possui cache
    - Não possui tratamendo de dados
    - Não tem contexto de estados
- GraphQL (semelhante AO fetchQL)
  - Vantagens
    - Bastante leve
    - Baseado em Promises(async/await)
    - Suporte ao Typescript
    - **Isomórfico**
  - Desvantagens
    - Não possui cache
    - Não possui tratamendo de dados
    - Não tem contexto de estados
- uRQL
  - Vantagens
    - Bastante leve e focado em performance
    - Altamente extensível
    - Junto com Exchanges possui caching
    - Possui suporte offline
  - Desvantagens
    - Muito nova(pouso material sobre)
    - Pouca adoção
- Relay Modern
  - Vantagens
    - Focado em performance
    - **Pré-compila as queries do GraphQL em build time(evita que o usuário baixe o parser).**
    - Possui sistema de caching/states
  - Desvantagens
    - Necessita de configurações a mais no tooling
    - Curva de aprendizado maior devivo a mais detalhes de funcionamento
- Apollo Client
  - Vantagens
    - Largamente utilizado no mercado
    - Possui sistema de caching/states(melhor de todos)
    - API simplificada com suporte a hooks
    - Muito material online
  - Desvantagens
    - Extremamente grande
    - Atualizações contantes com **Breaking Changes**


# Observações
- Possui apenas **uma rota**
