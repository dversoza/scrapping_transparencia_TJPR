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

## TODO

- [ ] Adicionar opção para extrair dados de serventias judiciais
- [ ] Adicionar opção para extrair dados de servidores
- [ ] Adicionar opção para extrair dados de receitas e despesas do tribunal
