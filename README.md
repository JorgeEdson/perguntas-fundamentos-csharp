### Perguntas e respostas sobre os fundamentos do C#

1. O C# é uma linguagem compilada, tipada e gerenciada, o que isto significa?
> Linguagem compilada significa que ela precisa de um <strong>Compilador</strong> para tansformar o <strong>Código-fonte</strong> em um <strong>Arquivo binário</strong> executável pelo <strong> Sistema Operacional</strong> de destino (Mac, Windows, Linux). Já a linguagem tipada refere-se ao uso de variáveis, classes e métodos com tipos específicos (int, string, decimal). Por fim, gerenciada significa que sua execução depende de um gerenciador (também é conhecido como Runtime). No caso do C# quem faz este gerenciamento é o <strong>CLR (Common Language Runtime)</strong>. O CLR gerencia serviços importantes como gestão de memória, segurança entre outros.

2. O que diferencia uma linguagem compilada de uma interpretada?
> A linguagem compilada precisa converter o nosso <strong>código-fonte</strong> inteiro para <strong>linguagem de máquina</strong> de uma só vez através de um programa chamado <strong>compilador</strong>. Nesse caso, o usuário recebe o código pronto para ser executado. Já a linguagem interpretada interpreta o <strong>código-fonte</strong> em partes por meio de um programa chamado <strong>interpretador</strong>, que irá então converter nosso código para <strong>linguagem de máquina</strong>. Assim, é necessário que o código seja interpretado e convertido para o cliente e então executado (o código não vem pronto igual ocorre na linguagem compilada). 

3. Explique como o C# funciona
> Primeiro o código em C# é compilado para a Intermediate Language (IL). Depois o CLR pega o IL e compila-o para código nativo do sistema operacional, ou seja, código executável.

4. O que é o CLR?
> O <strong>CLR (Common Language Runtime)</strong> é o gerenciador da linguagem C#. O CLR recebe o código gerenciado, compila-o em código que a máquina entenda e o executa. Além disso, o CLR é responsável pela gestão de memória, segurança, entre outros. Assim, podemos concluir que o CLR é a infraestrutura responsável pela execução do programa

5. O que é IL?
> IL é a <strong>Intermediate Language</strong>, ou seja, é uma linguagem intermediária gerada pelos compiladores que pretendem rodar em cima do CLR. O compilador compila o código-fonte e o transforma em IL.

6. O que é um Framework?
> O <strong>Framework</strong> é uma estrutura composta por um conjunto de bibliotecas e códigos genéricos que permitem o desenvolvimento de sistemas e aplicações. Um framework funciona como uma espécie de template o qual oferece certos artifícios estruturais básicos para criação de alguma aplicação ou software.

6. O que é o .NET?
> O <strong>.NET</strong> é uma plataforma de desenvolvimento atualmente open-source, criada pela Microsoft, e que é composta por uma biblioteca padrão, um compilador e uma máquina virtual. Esses componentes da plataforma possibilitam a criação de códigos em algumas linguagens, como C#, VB.NET e F#.

7. O que é o .NET Standard?
> <strong>.NET Standard</strong> é uma especificação formal de APIs .NET que estão disponíveis em várias implementações .NET. A motivação por trás do .NET Standard foi estabelecer maior uniformidade no ecossistema .NET.

8. Explique o que é versão semântica
> A <strong>versão semântica</strong> é uma convenção formal para determinar o número de versões de novos lançamentos de software. A norma ajuda os utilizadores de software a compreender a gravidade das mudanças em cada nova distribuição. Um projeto que utiliza a versão semântica deve possuir um número <strong>Maior (Major number)</strong>, <strong>Menor (Minor number)</strong> e de <strong>correção (Patch number)</strong> para cada lançamento. Por exemplo, a versão `1.2.3` indica uma versão maior de 1, uma versão menor de 2 e um número de correção de 3.

9. O que significa LTS na versão do software?
> <strong>LTS</strong> significa apoio a longo prazo. Aqui, apoio significa que ao longo da vida de um lançamento há um compromisso de atualizar, corrigir e manter o software. Para um LTS, existe um ciclo de desenvolvimento mais curto, onde engenheiros e colaboradores acrescentam ao corpo da versão.

10. O que é um Runtime?
> <strong>Runtime</strong> descreve software/instruções que são executadas enquanto o programa está em execução, especialmente as instruções que não são escritas explicitamente, mas que são necessárias para a execução adequada do código.

11. O que é um SDK?
> <strong>SDK</strong> significa kit de desenvolvimento de software ou <strong>devkit</strong> para abreviar. É um conjunto de ferramentas e programas de software utilizados pelos programadores para criar aplicações para plataformas específicas. As ferramentas SDK incluem uma gama de coisas, incluindo bibliotecas, documentação, amostras de código, processos e guias que os programadores podem utilizar e integrar nas suas próprias aplicações. Os SDK são concebidos para serem utilizados em plataformas ou linguagens de programação específicas.

12. O que é um CLI?
> <strong>CLI</strong> significa <strong>Command Line Interface</strong> ou <strong>Interface de linha de comando</strong>. CLI é um programa de linha de comando que aceita a entrada de texto para executar funções do sistema operacional. Por exemplo, o gerenciador de pacotes <strong>NPM</strong> utiliza linha de comando para instalar componentes necessários ao desenvolvimento de software.

13. Cite 3 tipos de projetos que temos no .NET?
> <strong>Biblioteca de classes</strong>, <strong>Aplicativo Console</strong>, <strong>Aplicativo WEB ASP.NET Core</strong> e <strong>API WEB ASP.NET Core</strong>.

14. O que é uma Solution?
> Uma <strong>solução</strong> uma espécie de container de trabalho que contém uma coleção de projetos, juntamente com informações sobre as dependências entre esses projetos.

15. Qual comando para executar uma aplicação .NET?
> dotnet run

16. Qual comando para compilar uma aplicação .NET?
> dotnet build

17. Qual comando para publicar uma aplicação .NET?
> dotnet publish

18. Qual nome do método principal de um Console App?
> Main()

19. O que significa Debug?
> <strong>Debug</strong> ou <strong>Depuração</strong> é o processo de detecção e remoção de erros existentes ou potenciais (também chamados de 'bugs') num código de software que pode causar o seu comportamento inesperado ou a sua queda. Para evitar o funcionamento incorrecto de um software ou sistema, a depuração é utilizada para encontrar e resolver bugs ou defeitos.

### ` 🌐 Referências`
- <p> Perguntas para entrevista de C# e .NET: https://balta.io/blog/perguntas-entrevista-csharp</p>

- <p> Por que utilizar C#?: https://balta.io/blog/csharp</p>
