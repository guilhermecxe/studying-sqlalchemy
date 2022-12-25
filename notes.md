# Anotações

## Erros

- "ArgumentError: relationship expects a class or mapper argument"
    - Solução: verificar se o primeiro argumento de `relationship` está referenciando a classe da tabela, não o nome da tabela no banco de dados.
    - Fonte: https://stackoverflow.com/questions/25002620/argumenterror-relationship-expects-a-class-or-mapper-argument