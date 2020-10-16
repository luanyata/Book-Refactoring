# Guia Rápido com Extrategia de Refatoração

## Extração de Função (Extract Function):

### Definição:

Extrai uma fatia do código de uma função para transformar em outra função.

### Estratégia:

- Observar o fragmento de código que será extraido em busca de qualquer variável que não estará mais no escopo depois que eu tiver realizado a extração do código em sua própria função.

- Variáveis que não serão alteradas podem ser passadas como parametro para a nova função.

- Variáveis que tem seu valor alterado devem ser retornada no termino da execução da função
