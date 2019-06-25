# Proposta de arquitetura
## Dremio
A utilizacao do Dremio como barramento de dados ira unificar e facilitar as interfaces de consultas e armazenamento.
Outra vantagem da utilizacao dessa arquitetura sera a facilidade de portar para outra stack, pois o Dremio bascimente precisa de um storage, e no minimo 2 servidores (coordinator nodes, worker node).

Um artigo muito interessante sobre a ferramenta pode ser visto [aqui](https://medium.com/data-hackers/o-que-%C3%A9-e-como-funciona-o-dremio-4ff2c7a6d119).

## Stream data
Montei a arquitetura pensando numa ferramenta que tera dados alimentando em real-time, tanto os web crawlers, quanto os possiveis novos apps, o Dremio ira orquestrar, pode ser utilizado Python para tranformacoes mais complexas, por exemplo, o problema de Real <> USD.

![alt text](https://github.com/whrocha/wine_data_structure/blob/master/dremio_vagas.com_example.png)

## Custo
![alt text](https://github.com/whrocha/wine_data_structure/blob/master/cost.png)
