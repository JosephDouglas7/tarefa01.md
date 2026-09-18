## Testes de Unidade  

são verificações automatizadas que avaliam pequenas partes isoladas do código (funções, métodos ou classes) para garantir que funcionem conforme esperado. Eles ajudam a detectar erros cedo, reduzem custos de manutenção e aumentam a qualidade do software. 

A linguagem de programação utilizada foi o Python, escolhida pela sua versatilidade e ampla adoção em projetos de automação e testes. O stack empregado foi o Selenium, uma poderosa ferramenta para automação de navegadores que permite validar fluxos de interface e interações do usuário em aplicações web. 

O Pytest é um framework de testes para Python que se destaca pela simplicidade e flexibilidade. Ele permite escrever testes curtos e legíveis usando apenas assert, mas também suporta cenários complexos com fixtures, parametrização e uma ampla gama de plugins. Sua sintaxe é simples, já que basta utilizar assert para validar resultados, e ele possui descoberta automática de arquivos e funções de teste seguindo convenções como test_*.py. Além disso, oferece fixtures para configurar e limpar ambientes de teste de forma modular, parametrização para executar o mesmo teste com diferentes entradas e centenas de plugins disponíveis para relatórios, paralelização e integração com outras ferramentas. Entre suas vantagens estão a fácil integração em pipelines de CI/CD, relatórios claros que mostram valores esperados e obtidos em falhas, além de uma comunidade ativa que mantém documentação extensa e suporte contínuo. 

### PYTEST

[pytest](https://pypi.org/project/pytest-cov/)  

[Documentação pytest](https://docs.pytest.org/en/stable/)

[pytest sem cov](https://pypi.org/project/pytest/)
         


O Visual Studio é uma IDE completa da Microsoft, muito utilizada para desenvolvimento em C#, C++, Python e outras linguagens, e se destaca por integrar ferramentas avançadas de debug que permitem inspecionar variáveis, controlar a execução do código e diagnosticar problemas em tempo real. Ele oferece um ambiente integrado que reúne editor de código, compilador, depurador, gerenciador de pacotes e suporte a múltiplas linguagens, além de contar com suporte multiplataforma para depuração local, remota e até em produção, como em Azure, dispositivos móveis e navegadores. Também funciona bem em pipelines de CI/CD, integrando-se a processos de build e testes automatizados.

Entre as ferramentas de depuração disponíveis estão os breakpoints, que podem ser simples, condicionais ou de função, usados para pausar a execução em locais estratégicos; os comandos Step Into, Step Over e Step Out, que permitem avançar linha a linha, entrar em funções ou sair delas; e a inspeção de variáveis por meio das janelas Autos, Locals e Watch, que monitoram valores e expressões complexas. O recurso DataTips mostra valores de variáveis diretamente no editor durante a execução, enquanto o Call Stack exibe a pilha de chamadas para entender o fluxo do programa. Há ainda alertas configuráveis para capturar exceções específicas, suporte a depuração multithread para controlar aplicações com várias threads, e o recurso Edit and Continue, que permite alterar o código durante a depuração sem reiniciar a aplicação. Na edição Enterprise, o IntelliTrace grava o histórico de execução para que seja possível “voltar no tempo” e analisar estados anteriores. Além disso, o Visual Studio inclui ferramentas de diagnóstico para análise de CPU, memória e desempenho em tempo real, tornando o processo de depuração mais completo e eficiente.


### Tutorial de como fazer um CRUD em linguagem python  

**Passo 1: Criar o arquivo principal (crud.py)** 
Com as funções de Create, Read, Update e Delete. 

**Passo 2: Criar os testes (test_crud.py)**  
pode ser usado o pytest para validar cada operação do CRUD 

**Passo 3: Executar os testes**  

Esse tutorial mostra de forma prática como criar um CRUD em Python para armazenar dados e o Pytest para validar cada operação. Primeiro, você constrói funções para Create, Read, Update e Delete, depois escreve testes automatizados que verificam se cada ação funciona corretamente, e por fim executa tudo com o Pytest para obter relatórios claros. É uma abordagem simples, modular e ideal para aprender a testar operações de banco de dados em Python.

**Referências do Tutorial** 

[paginadoale](https://paginadoale.com.br/2025/10/crud-em-python-com-sqlite/?utm_source=copilot.com) 

[python_dev](https://python.dev.br/blog/python-e-banco-de-dados-sqlite/?utm_source=copilot.com) 

[qadrlabs](https://qadrlabs.com/post/building-a-crud-rest-api-with-flask-and-sqlite?utm_source=copilot.com) 

#### Mocks objects
Mocks Objects são objetos simulados usados em testes de unidade para substituir dependências reais, como bancos de dados ou APIs, permitindo que o código seja testado de forma isolada, rápida e controlada. Eles não apenas retornam dados pré-definidos, mas também verificam se métodos foram chamados corretamente, quantas vezes e com quais parâmetros. Em essência, mocks são objetos que imitam o comportamento de componentes reais e são usados para isolar dependências externas, garantindo que os testes sejam determinísticos — ou seja, sempre com o mesmo resultado — e rápidos, já que não acessam rede ou disco.

Esses objetos têm funções principais como retornar dados previsíveis, fornecendo respostas controladas sem depender de sistemas externos; verificar interações, checando se métodos foram chamados, quantas vezes e com quais argumentos; e simular erros, criando cenários difíceis de reproduzir com dependências reais. Exemplos de uso incluem o módulo unittest.mock em Python, que simula dependências em testes unitários; o Mockito em Java, que cria mocks para verificar chamadas de métodos; e o Jest em JavaScript, usado para simular funções e módulos.


