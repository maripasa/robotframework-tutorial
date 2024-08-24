# ROBOTFRAMEWORK CRASHCOURSE
## Sumário
<!--ts-->
- [ROBOTFRAMEWORK CRASHCOURSE](#robotframework-crashcourse)
  - [Sumário](#sumário)
  - [1. Motivação e Apresentação](#1-motivação-e-apresentação)
  - [2. Introdução antes da introdução](#2-introdução-antes-da-introdução)
  - [3. Introdução ao robotframework](#3-introdução-ao-robotframework)
  - [4. Dicas antes de utilizar o robotframework](#4-dicas-antes-de-utilizar-o-robotframework)
  - [](#)
<!--te-->

## 1. Motivação e Apresentação



## 2. Introdução antes da introdução

- **O que é QA?**

*Quality Assurance* significa “Garantia de Qualidade” e garante que a mercadoria seja entregue ao cliente em ótimas condições e com a qualidade esperada por ele. Isso evita que o produto seja entregue com problemas e erros durante o processo.

- **O que eu vou fazer enquanto no QA?**

Testar tudo até achar uma situação em que o código quebra, o professor as vezes pode inventar algumas coisas meio fora da àrea do QA, então pode sempre esperar mais do que só testes.

- **O que tenho que aprender enquanto no QA?** 

Tem muitas coisas para aprender nessa área, muito overlap com áreas diferentes também, você acaba aprendendo um belo básico de frontend, e um belo básico de backend, então é uma área ótima para começar. Existe uma **infinidade** de diferentes [ferramentas](https://roadmap.sh/qa), mas a que eu vou estar introduzindo agora é a **robotframework**, a ferramenta principal de testes do QA.

- **O que são testes automatizados**?

Como o nome já diz, são códigos que simulam o uso de um usuário, assegurando que tudo está ocorrendo como o planejado. No minimo do minimo, testamos apenas se o caminho para executar uma função da aplicação está acessível, no ideal testamos todos os _testcases_.

- **Eu não sei NADA de programação, nasci ontem não tenho git instalado nem ubuntu nem o vscode nem conta no github, o que eu faço?**
1. [Git e Github](./tools/git.md) **!! IMPORTANTÍSSIMO !!**
2. [Python e pip](./tools/python.md) **!! IMPORTANTÍSSIMO !!**
3. [Vscode](./tools/python.md)

- **Eu ODIEI o jeito que você ensina, ODIEI esse repositório, eu tenho ODIO no coração, a brisa do verão É REFRESCANTE DEMAIS, ODEIO suco de manga ser MUITO DOCE, estou com muita raiva. O que eu faço? (Ou se quiser aprofundar mais no robotframework):**
1. [ROBOT FRAMEWORK KICKOFF](https://www.youtube.com/watch?v=wdtqpQrQ598&list=PL5ipcSFH2tk8RWxtvuaOK-qpdAvlWkSoo)
2. [ROBOT FRAMEWORK TUTORIAL - Learn Robot Framework](https://www.youtube.com/playlist?list=PLL34mf651faORDOyJrk0E6k9FM-wKgfPV)
3. [RestAPI Testing using Robot Framework+Python For Beginners](https://www.youtube.com/playlist?list=PLUDwpEzHYYLvMLbma_Rp-6jrrpxkeH0VJ)
4. Se você vem do LASIC, tem ótimos cursos em uma das contas da udemy do laboratório.
## 3. Introdução ao robotframework
```
*** Settings ***
Library  SeleniumLibrary
```
- **O que é o robotframework?**

É, antes de tudo, uma framework de testes, ele junta várias ferramentas de testes automatizados em forma de libraries, unificando-as em uma plataforma de fácil utilização.

O robotframework é muito abstraído, se você alguma vez já se assustou com python por ser uma linguagem que você "só escreve código e ela funciona", robotframework vai te impressionar.

Por ser uma library em cima do python que o torna, de algum jeito, ainda mais simples, pode se esperar que não tem foco em eficiência de processamento de código assim como outras linguagens. Você vai ver isso em algumas organizações de projeto, como a que vou explicar aqui.

Ele junta ferramentas como:
- [playwright](https://playwright.dev/)
- [appium](https://appium.io/)
- [selenium](https://www.selenium.dev/)
- e muitas outras!

## 4. Dicas antes de utilizar o robotframework

- É bom ver o crash course também de [python](/tools/python.md) e depois o de [git](/tools/git.md).

- Na área do Vscode, uma extensão muito boa para robotframework é essa:
![alt text](/media/image.png)

##