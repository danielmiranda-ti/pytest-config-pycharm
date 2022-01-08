# pytest-config-pycharm

## Configurações:
- Para utilizar o pytest como o executor padrão de testes no Intellij é necessário realizar a configuração em `File -> Settings... -> Tools -> Python Integrated Tools` em `Testing - Default test runner` escolha `pytest`  
## Para executar os testes e gerar o relatório de cobertura em html execute o comando:

``pytest --cov-report html:cov_html --cov=src/ tests/``

## Para executar os testes e gerar o relatório no terminal e identificar as linhas que faltam ser cobertas no arquivo, execute o seguinte comando:

``pytest --cov-report term-missing:skip-covered --cov=src/ tests/``

## Referências:
* [Pytest-cov](https://pytest-cov.readthedocs.io/en/latest/reporting.html)
