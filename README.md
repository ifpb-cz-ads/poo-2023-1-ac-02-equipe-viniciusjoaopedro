## 2.03 Atividade colaborativa
Respostas das questões 1 a 8 do livro Batista & Moraes (2013).

## 🤝 Alunos: Vinícius da Silva Ribeiro e Joao Pedro Oliveira Santos

## ✔️ Questão 1: Explique a função da Máquina Virtual Java(JVM)

Máquina Virtual Java (Java Virtual Machine) - é o responsável por interpretar o código Java complilado em formato bytecode (.class) e traduzir para o sistema operacional (Windows, Linux, Mac, etc.) em que estiver instalado. Sendo esse o principal motivo pelo qual o Java é multiplataforma.

## ✔️ Questão 2: Qual a diferença entre JRE e JDK ?

JRE - Java Runtime Environment (Ambiente de Tempo de Execução Java) é composto pela Máquina Virtual Java (JVM) e pelas bibliotecas. É usado para executar as aplicações da plataforma Java.

JDK - Java Development Kit (Kit de Desenvolvimento Java) contém o JRE e um conjunto de ferramentas que permitem desenvolver uma aplicação Java.

Assim, o JRE possui os itens necessários para o Java rodar, mas não para desenvolver uma aplicação Java. Já o JDK possui tanto o JRE quanto os recursos necessários para desenvolvedores.

## ✔️ Questão 4: Compile o programa desenvolvido no exercício anterior. A seguir apague o arquivo .class gerado e tente executar o programa. O que aconteceu?

Ao tentar executar o programa após excluir o arquivo .class ocorrerá um erro de tempo de execução como `ClassNotFoundException`, pois a JVM (Máquina Virtual Java) não tem mais o arquivo em formato bytecode (.class) para carregar a classe e executar corretamente.

## ✔️ Questão 5: Mude o nome do método “main” para “start”, compile e execute. O que aconteceu?
Ocorreu o seguinte erro ao compilar o programa:

`Error: Main method not found in class BM_Q3, please define the main method as:
   public static void main(String[] args)`
   
O erro ocorreu pois não havia um método principal no código.

## ✔️ Questão 7: Experimente escrever todo o programa anterior em maiúsculo, compile e execute. O que aconteceu?

Ocorreu vários erros durante a compilação, principalmente por não ter nenhuma classe a ser chamada no programa, era como se não tivesse nada escrito nele. Fora os erros de sintaxe que consequentemente ocorreram.

## ✔️ Questão 8: Experimente salvar o arquivo com um nome diferente do nome da classe, compile e execute. O que aconteceu?

Ao tentar compilar o arquivo Java com um nome diferente do da classe ocorreu uma falha `(error: <identifier> expected)`. Isso ocorre porque o nome da classe tem que ser exatamente igual ao nome do arquivo, incluindo letras maiúsculas e minúsculas. Caso contrário, o compilador Java não poderá encontrar a definição da classe e gerará um erro de compilação.
