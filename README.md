# Quality Assurance - Plano de Testes e Gestão de Bugs

Curso da Alura sobre como realizar testes estruturados e controle de qualidade.

## Objetivo Final &#x1F3AF;

Realizar um controle de teste de uma página de login.

URL do curso -> [Quality Assurance - Plano de Testes e Gestão de Bugs](https://cursos.alura.com.br/course/quality-assurance-plano-testes-gestao-bugs)

![Quality Assurance - Plano de Testes e Gestão de Bugs](https://www.alura.com.br/assets/api/share/curso-quality-assurance-plano-testes-gestao-bugs.png)

## Links Úteis &#x1F517;
* [Lighthouse](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=en-US) - Extensão do Google para medir / testar a qualidade do site.

## Siglas &#x1F5FA;
* **QA** - ***Q**uality* ***A**ssurance* - Garantia de qualidade.

## Atalhos &#x2328;
*

***

## 01 - Testes e Cenários de Testes &#x1F516;
* Testes funcionais, são os testes definidos de acordo com os requisitos funcionais do software.
* Que podemos pensar nos nossos testes construindo fluxos de testes ou tabelas de decisão conforme as regras de negócio do nosso projeto.
* Conceitos de Cenários de testes definem “**O que**” deve ser testado, enquanto os Casos de Testes definem “**Como**”, ou seja, o passo a passo. O caso de teste é mais detalhado.
* Como escrever Casos de testes utilizando BDD, sigla para *Behavior driven development* (desenvolvimento guiado por comportamento ou desenvolvimento orientado a comportamento, numa tradução livre) com intuito de escrever testes guiados pelo comportamento do usuário e pelos negócios. Para tal, usamos a semântica **Dado**, **Quando** e **Então**.
* Um Plano de teste define e comunica a intenção e esforço do teste. Serve, por exemplo, para ganhar a aceitação e aprovação dos envolvidos, comunicar e justificar prazo de teste planejado.

### 01 - Casos de Teste
* Metodologias usadas em um cenário de testes.
* Etapas de um cenário de testes.

***

## 02 - Qualidade &#x1F516;
* Que qualidade de software, pode ser entendida como um conjunto de características a serem satisfeitas, de modo que o produto atenda às necessidades de seus usuários. Falamos de fazer o software certo para o usuário certo.
* Num time ágil, o papel de QA exige ser generalista, olhar o software como um todo de maneira que minimize custos, tempo e efeitos indesejáveis. Isso deve ser feito o mais breve o possível, ajudando assim a construir um projeto melhor.
* No **ciclo de desenvolvimento de software em cascata** as etapas do projeto são feitas uma após a outra de forma síncrona.,Portanto, neste esquema é dada muita ênfase às fases de análise e projeto antes de partirmos para a programação de fato. Uma desvantagem é que dessa forma fica difícil prevenir erros, dado que a etapa de testes fica apenas no final.
* Já nos modelos ágeis, a abordagem iterativa enfatiza a entrega rápida de uma aplicação em componentes funcionais completos, com entregas menores. A pessoa responsável de QA consegue participar de todo o processo de desenvolvimento.
* Critérios de aceite são os valores máximos ou mínimos aceitáveis para uma funcionalidade ser aceita.
* Definição de pronto (*DoD - definition of done*) são pontos que definem se uma atividade foi concluída ou não. Ela deve valer para o projeto como um todo.

### 01 - O que é Qualidade
* Quais os preceitos de qualidade.

### 02 - Qualidade ao Longo do Ciclo
* O que é o modelo cascata.
* O que é o modelo ágil.

### 03 - Critérios de Aceite
* Quando que uma funcionalidade pode se considerar aceitável.

### 04 - Definição de Pronto
* Quando um software / funcionalideade pode ser considerado pronto.

***

## 03 - Aprofundando nos Tipos Testes &#x1F516;
* **Teste de regressão**: é uma técnica de teste a ser aplicada quando surgem novas versões mais recentes do software e garante que não surjam novos defeitos em componentes já analisados.
* **Teste de sanidade**: é o subconjunto do teste de regressão e também é realizado quando não temos tempo suficiente para fazer o teste mais elaborado. Ele tem um nível superficial e verifica se as funcionalidades mais críticas do sistema estão conforme o esperado.
* **Testes de limite**: consistem em testar os valores mínimo e máximo (ou primeiro e último valores) de uma partição. Essa técnica é geralmente usada para testar requisitos que exigem um intervalo de números (incluindo datas e horas).
* **Teste de transição**: de estados é utilizado para testar a capacidade que o software tem de entrar em e sair de estados definidos através de transições válidas e inválidas.
* **Testes não-funcionais**: tem como objetivo testar aspectos do software que não são associados a funcionalidades. Ex: escalabilidade, desempenho, segurança.
* **Testes de performance**: são um conjunto de testes que visam analisar o desempenho. Entre eles, temos.
* **Teste de carga**: que tem como objetivo verificar o desempenho de um sistema quando ele é submetido a cargas variáveis de usuários ou transações.
* **Teste de capacidade**: parecido com o de carga, tem como objetivo identificar os limites da aplicação, ou seja, quantos usuários simultâneos ou chamadas por segundo a aplicação é capaz de suportar dentro dos parâmetros de qualidade definidos.
* **Teste de stress**: verifica a performance de um sistema quando é submetido a cargas que estão no limite ou acima do limite especificado inicialmente.
* **Teste de usabilidade**: tem como objetivo observar usuários reais usando o software para descobrir problemas e pontos de melhorias.

### 01 - Teste Relacionado a Mudança
* Ajustar o que deve ser testado.

### 02 - Mais Técnicas de Teste
* O que é o **teste de limite**.
* O que é **teste de estado**.
* O que é **teste exploratório**.

### 03 - Testes Não-Funcionais
* O que são testes não funcionais.