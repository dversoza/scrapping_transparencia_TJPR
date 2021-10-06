# WebScrapper - Portal da Transparência TJPR

> Transparência: verdadeira e simplificada

Este script simples extraí dados do portal da transparência do TJPR e retorna CSV simples e consultáveis com resumo dos resultados financeiros das serventias e demais órgãos vinculados ao Tribunal.

## Features

- Atualmente extraí apenas dados de resultados financeiros das Serventias Extrajudiciais do TJPR

## Execução

Para executar, instale a biblioteca requests caso não tenha, com:

```sh
pip install requests
```

Então, apenas execute o `main.py` no seu terminal e escolha a opção simples ou detalhada.

```sh
python.exe main.py
```

- Na opção simples, você verá apenas o resultado final da extração quando finalizada
- Na opção detalhada, você verá linha a linha a extração dos dados

## Resultado

Ao final, você terá um CSV com todos os dados, e poderá visualizá-los em tabela com estrutura semelhante a esta:

| Comarca / Serventia Extrajudicial                                                                                         |      2018       |       2019       |      2020       |       2021       |   Total Geral    |
| ------------------------------------------------------------------------------------------------------------------------- | :-------------: | :--------------: | :-------------: | :--------------: | :--------------: |
| 8º Serviço de Registro de Imóveis do Foro Central da Comarca da Região Metropolitana de Curitiba                          | R$ 5.440.730,81 | R$ 12.778.474,63 | R$ 9.861.284,99 | R$ 13.257.083,50 | R$ 41.337.573,93 |
| 1º Serviço de Registro de Imóveis do Foro Central da Comarca da Região Metropolitana de Londrina                          | R$ 3.837.116,05 | R$ 9.120.386,31  | R$ 8.458.784,80 | R$ 6.567.534,67  | R$ 27.983.821,83 |
| 6º Serviço de Registro de Imóveis do Foro Central da Comarca da Região Metropolitana de Curitiba                          | R$ 3.253.248,89 | R$ 8.508.878,89  | R$ 6.801.850,23 | R$ 4.325.247,56  | R$ 22.889.225,57 |
| 1º Serviço de Registro de Imóveis do Foro Central da Comarca da Região Metropolitana de Maringá                           | R$ 2.543.310,21 | R$ 5.260.576,85  | R$ 5.528.040,95 | R$ 5.256.915,15  | R$ 18.588.843,16 |
| 2º Serviço de Registro de Imóveis do Foro Central da Comarca da Região Metropolitana de Curitiba                          | R$ 1.707.215,29 | R$ 6.224.611,35  | R$ 4.721.166,74 | R$ 5.913.923,44  | R$ 18.566.916,82 |
| \*\*\*                                                                                                                    |     \*\*\*      |      \*\*\*      |     \*\*\*      |      \*\*\*      |      \*\*\*      |
| 1º Serviço de Registro de Imóveis do Foro Regional de São José dos Pinhais da Comarca da Região Metropolitana de Curitiba | R$ 2.200.614,00 | R$ 5.196.023,24  | R$ 4.662.502,86 | R$ 5.850.969,91  | R$ 17.910.110,01 |
| 2º Serviço de Registro de Imóveis do Foro Central da Comarca da Região Metropolitana de Maringá                           | R$ 2.618.460,03 | R$ 4.887.744,57  | R$ 4.999.803,24 | R$ 4.307.329,32  | R$ 16.813.337,16 |

## TODO

- [ ] Adicionar opção para extrair dados de serventias judiciais
- [ ] Adicionar opção para extrair dados de servidores
- [ ] Adicionar opção para extrair dados de receitas e despesas do tribunal
