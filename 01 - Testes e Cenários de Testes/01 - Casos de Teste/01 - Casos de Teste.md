As etapas que podem ser usadas para criar um caso de teste são as seguintes:

| Etapa                     | Descrição                                                 |
| ---                       | ---                                                       |
| **Casos de Teste**        | É um nome exclusivo para identificar esse caso de teste |
| **Pré-condições**         | Indica o estado do sistema para executar o caso de teste |
| **Procedimentos**         | Os passo necessários para chegar ao resultado esperado |
| **Resultado esperado**    | O que se espera |
| **Dados de entrada**      | Dados necessários para executar uma ação do sistema (ex. usuário e senha em tela de login) |
| **Critérios especiais**   | Se há critérios especiais |
| **Ambiente**              | Onde deve ser executado caso de teste |
| **Implementação**         | Manual ou automatizada |
| **Iteração**              | Número da iteração |

Uma metodologia usada é a **BDD** (*Behavior Driver Development*) - Desenvolvimento Guiado por Comportamento, que é uma forma mais rápida de se testar o software.

Essa metodologia inclui as seguintes etapas:

* Dado:
    * Quais pré-condições devem ser verdadeiras para que eu execute o teste?
        * Como exemplo poderia ser escrito: "Dado um usuário...".
* Quando - e:
    * Qual ação será executada no sistema que fornecerá o resultado validado?
* Então:
    * De acordo com a ação disparada qual o resultado esperado?