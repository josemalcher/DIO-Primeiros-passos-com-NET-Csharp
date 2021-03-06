# Digital Innovation One - Primeiros passos com .NET + C#

https://web.digitalinnovation.one/course/primeiros-passos-com-net-c

Nesse curso o aluno terá o primeiro contato com a plataforma .NET e sua linguagem C# aprendendo onde e como utilizá-las. O especialista vai mostrar como preparar ambiente, lidar com erros, classes e objetos.

## <a name="indice">Índice</a>

1. [O que é .NET?](#parte1)     
2. [Iniciando com .NET](#parte2)     
3. [Conhecendo o C#](#parte3)     
4. [Conhecendo variáveis e instruções](#parte4)     
5. [Classes e objetos essenciais em C#](#parte5)     
6. [Trabalhando com structs, interfaces e enums](#parte6)     
7. [Uma síntese do que é .NET](#parte7)     
---


## <a name="parte1">1 - O que é .NET?</a>

- Conhecendo o framework
- Como e aonde usar .NET
- Certifique seu conhecimento

```
Em qual década a Microsoft foi criada?
1980
1970
1960
1950
1990

R: 1970
```

```
Qual é a ordem correta de atuação de cada componente dentro do .NET?
Nenhuma das alternativas.
Código Fonte > Compilador da linguagem > Linguagem Intermediária > CLR > Linguagem de Máquina
Código Fonte > CLR > Linguagem de Máquina
Código Fonte > CLR > Linguagem Intermediária > Compilador da linguagem > Linguagem de Máquina
Linguagem de Máquina > CLR > Linguagem Intermediária > Compilador da linguagem > Código Fonte

R: Código Fonte > Compilador da linguagem > Linguagem Intermediária > CLR > Linguagem de Máquina
```

```
Qual dos fatos a seguir não é verdadeiro?
Em 2014 o empresário Satya Nadella compra a Microsoft e se torna sócio majoritário da empresa.
O C# 1.0 foi lançado em 2002.
O .NET 1.0 foi lançado em 2000.
Em 2010 a Microsoft lança comercialmente o Windows Azure.
O Roslyn é um novo compilador C# criado a partir de 2013.

R: Em 2014 o empresário Satya Nadella compra a Microsoft e se torna sócio majoritário da empresa.
```

```
O que acontece a partir de 2020 com relação ao .NET?
O .NET Framework deixará de ser evoluido, mantendo-se a evolução apenas do .NET Core, que passará se chamar apenas .NET.
A Microsoft irá criar uma nova implementação open source e multiplataforma.
A Microsoft irá vender seus códigos para a Oracle.
Todas as alternativas estão corretas.
VB.NET passará a ser a única versão suportada na plataforma.

R: O .NET Framework deixará de ser evoluido, mantendo-se a evolução apenas do .NET Core, que passará se chamar apenas .NET.
```

```
O que era o projeto Mono criado por Miguel de Icaza em 2001?
Uma nova implementação do Java, focado em Windows.
Uma nova linguagem de programação.
Um projeto para elaboração de monografias.
Uma reimplementação do .NET patrocinado pela Microsoft, que viria a se chamar .NET Core.
Uma reimplementação black box do .NET, criado de forma independente por ele com foco em ser open source e multiplataforma.

R: Uma reimplementação black box do .NET, criado de forma independente por ele com foco em ser open source e multiplataforma.
```

```
O .NET Core é uma implementação open source e multiplataforma do .NET Standard. Qual dos itens abaixo é uma das outras implementações?
.NET Framework
C#
.NET Forever
CLR
Mini .NET

R: .NET Framework
```

```
Qual o foco da Microsoft a partir de 2014?
Sistemas Operacionais Linux.
Docker.
Sistemas Operacionais Windows
Java.
Cloud.

R: Cloud.
```

```
Em 1999, Jason Zander ajudou na criação de um CLR. Qual o significado de CLR?
Common Language Reactive
Converter Language Runtime
Common Literal Runtime
Cascade Language Runtime
Common Language Runtime

R: Common Language Runtime
```

```
Em qual ano surgiu a primeira versão do Visual Studio?
2002
1970
1995
1997
2000

R; 1997
```

```
Qual linguagem de programação começou a ser criada pela Microsoft em 1999 com ajuda de Anders Hejlsberg?
FoxPro
Visual Basic
C#
F#
C++

R: C#
```



[Voltar ao Índice](#indice)

---


## <a name="parte2">2 - Iniciando com .NET</a>

- Preparando o ambiente
- Conhecendo a CLI do .NET
- Criando uma aplicação console
- Certifique seu conhecimento

```
Qual o comando para criar uma aplicação console via CLI do .NET com o nome 'Teste'?
dotnet new console -n Teste
dotnet build Teste
dotnet new console Teste
dotnet new Teste
dotnet new -h

R: dotnet new console -n Teste
```

```
O que faz o comando 'dotnet restore' na CLI do .NET?
Restaura os pacotes e dependências do projeto.
Executa a aplicação.
Publica a aplicação.
Cria um novo projeto.
Compila o código fonte e gera as DLL's.

R: Restaura os pacotes e dependências do projeto.

```

```
Qual é o comando da CLI do .NET para compilar o código fonte e gerar as DLL's?
dotnet build
dotnet run
Nenhuma das alternativas.
dontet --help
dotnet restore

R: dotnet build
```

```
O que significa CLI?
Common Literal Interface
Command Line Interface
Command Line Interactive
Common Language Intermediate
C# Language Interpreter

R: Command Line Interface
```

```
Qual dos itens abaixo não compõe o pacote de instalação do .NET SDK?
Bibliotecas de Desenvolvimento
CLI
C#
CLR
Visual Studio Code

R: Visual Studio Code
```

```
Qual dos itens abaixo é uma opção multiplataforma para edição/criação do meu código fonte em .NET?
Todas as alternativas são corretas.
Visual Studio Code.
Visual Studio.
Word.
Visual Studio for Mac.

R: Visual Studio Code.
```

```
Qual dos itens abaixo é necessário ter instalado na máquina para desenvolver aplicações .NET?
.NET SDK
Java
Nuget
Nenhuma das alternativas.
.NET Runtime

R: .NET SDK
```

```
O que é uma aplicação console?
Uma aplicação que depende do windows para ser executada.
Uma aplicação que é executada em um terminal.
Uma aplicação para trabalhar com chamadas HTTP Restful.
Uma aplicação que roda na web.
Todas as alternativas estão corretas.

R: Uma aplicação que é executada em um terminal.
```

```
Qual o comando para rodar uma aplicação .NET via CLI?
dotnet restore
dotnet new
dotnet build
dotnet run
dotnte publish

R: dotnet run
```

```
Qual o comando parâmetro para visualizar a documentação de ajuda da CLI do .NET?
--info
--help
build
new
--version

R: --help
```

[Voltar ao Índice](#indice)

---


## <a name="parte3">3 - Conhecendo o C#</a>

### O que é e como funciona o C#

![](mod03/img/conceitos_1.png)

![](mod03/img/conceitos_2.png)

![](mod03/img/conceitos_3.png)

![](mod03/img/conceitos_4.png)

![](mod03/img/conceitos_5.png)

![](mod03/img/conceitos_6.png)


### Estrutura do programa

![](mod03/img/estrutura_1.png)

![](mod03/img/estrutura_2.png)


[Códigos Demonstrados - mod03\solution](mod03/solution)

Questões

```
Qual dos itens a seguir é parte da estrutura de um programa C#?
Assemblies
Tipos
Membros
Namespaces
Todas as alternativas estão corretas.

R: Todas as alternativas estão corretas.
```

```
O código e os recursos de Linguagem Intermediária são armazenados no disco em um arquivo executável chamado:
C#
Assembly
Todas as alternativas estão corretas.
CLR
IL

R: Assembly
```

```
Qual dos itens a seguir é exemplo de tipo?
Campos
Métodos.
Classe.
Propriedades.
Todas as alternativas estão corretas.

R: Classe.
```

```
Qual o nome da compilação para converter o código de Linguagem Intermediária em instruções de máquina nativas?
build
Runtime
dll
CLR
JIT (Just in Time)

R: JIT (Just in Time)
```

```
O que um código C# gera ao ser compilado no comando "dotnet build"?
Nenhuma das alternativas.
Código compilado em Linguagem Intermediária.
Código CLR.
Código compilado em Linguagem de Máquina.
Código JIT.

R: Código compilado em Linguagem Intermediária.
```

```
Qual é a função do Garbage Collector?
Converter código compilado em Linguagem de Máquina.
Limpar objetos não utilizados da memória.
Restaurar os pacotes e dependências do projeto.
Converter código compilado em Linguagem Intermediária.
Gerenciar as exceptions da aplicação.

R: Limpar objetos não utilizados da memória.
```

```
Quem converte os assemblies em Linguagem de Máquina?
CLR
CLI
C#
Bibliotecas de Desenvolvimento
Visual Studio Code

R: CLR
```

```
Os assemblies gerados na compilação do C# geralmente possuem qual extensão?
.exe ou .dll
.jar
.cs ou .csproj
.sln
.doc

R: .exe ou .dll
```

```
Quando os programas C# são compilados, eles são fisicamente empacotados em:
Classes.
Assemblies.
Nenhuma das alternativas está correta.
Interfaces.
Campos.

R: Assemblies.
```

```
Qual dos itens a seguir é exemplo de membro?
Todas as alternativas estão corretas.
Assemblies.
Campos.
Interfaces.
Classe.

R: Campos.
```



[Voltar ao Índice](#indice)

---


## <a name="parte4">4 - Conhecendo variáveis e instruções</a>

![](mod04/img/tipo_01.png)

![](mod04/img/tipo_02.png)

![](mod04/img/tipo_03.png)

![](mod04/img/tipo_04.png)


**Utilizando instruções em Programas**

![](mod04/img/instrucoes_1.png)

![](mod04/img/instrucoes_2.png)

![](mod04/img/instrucoes_3.png)

![](mod04/img/instrucoes_4.png)


**Exemplificando o Conteúdo**

```csharp
using System;

namespace solution
{
    class Program
    {
        static void Main(string[] args)
        {
             static void Declaracoes()
        {
            int a;
            int b = 2, c = 3;
            const int d = 4;
            a = 1;
            Console.WriteLine(a + b + c + d);
        }

        static void InstrucaoIf(string[] args)
        {
            if (args.Length == 0)
            {
                Console.WriteLine("Nenhum argumento");
            }
            else if (args.Length == 1)
            {
                Console.WriteLine("Um argumento");
            }
            else
            {
                Console.WriteLine($"{args.Length} argumentos");
            }
        }

        static void InstrucaoSwitch(string[] args)
        {
            int numeroDeArgumentos = args.Length;
            switch (numeroDeArgumentos)
            {
                case 0:
                    Console.WriteLine("Nenhum argumento");
                    break;
                case 1:
                    Console.WriteLine("Um argumento");
                    break;
                default:
                    Console.WriteLine($"{numeroDeArgumentos} argumentos");
                    break;
            }
        }

        static void InstrucaoWhile(string[] args)
        {
            int i = 0;
            while (i < args.Length)
            {
                Console.WriteLine(args[i]);
                i++;
            }
        }

        static void InstrucaoDo(string[] args)
        {
            string texto;
            do
            {
                texto = Console.ReadLine();
                Console.WriteLine(texto);
            } while (!string.IsNullOrEmpty(texto));
        }

        static void InstrucaoFor(string[] args)
        {
            for (int i = 0; i < args.Length; i++)
            {
                Console.WriteLine(args[i]);
            }
        }

        static void InstrucaoForeach(string[] args)
        {
            foreach (string s in args)
            {
                Console.WriteLine(s);
            }
        }

        static void InstrucaoBreak(string[] args)
        {
            while (true)
            {
                string s = Console.ReadLine();

                if (string.IsNullOrEmpty(s))
                {
                    break;
                }

                Console.WriteLine(s);
            }
        }

        static void InstrucaoContinue(string[] args)
        {
            for (int i = 0; i < args.Length; i++)
            {
                if (args[i].StartsWith("/"))
                {
                    continue;
                }
                
                Console.WriteLine(args[i]);
            }
        }

        static void InstrucaoReturn(string[] args)
        {
            int Somar(int a, int b)
            {
                return a + b;
            }

            Console.WriteLine(Somar(1, 2));
            Console.WriteLine(Somar(3, 4));
            Console.WriteLine(Somar(5, 6));
            return;
        }

        static void InstrucoesTryCatchFinallyThrow(string[] args)
        {
            double Dividir(double x, double y)
            {
                if (y == 0)
                    throw new DivideByZeroException();

                return x / y;
            }

            try
            {
                if (args.Length != 2)
                {
                    throw new InvalidOperationException("Informe 2 números");
                }

                double x = double.Parse(args[0]);
                double y = double.Parse(args[1]);
                Console.WriteLine(Dividir(x, y));
            }
            catch (InvalidOperationException e)
            {
                Console.WriteLine(e.Message);
            }
            catch (Exception e)
            {
                Console.WriteLine($"Erro genérico: {e.Message}");
            }
            finally
            {
                Console.WriteLine("Até breve!");
            }
        }

        static void InstrucaoUsing(string[] args)
        {
            using (System.IO.TextWriter w = System.IO.File.CreateText("teste.txt"))
            {
                w.WriteLine("Line 1");
                w.WriteLine("Line 2");
                w.WriteLine("Line 3");
            }
        }
        }
    }
}

```

![](mod04/img/array_1.png)

![](mod04/img/array_2.png)

![](mod04/img/array_3.png)

![](mod04/img/array_4.png)

![](mod04/img/array_5.png)

![](mod04/img/array_6.png)

**Questões**

```
Qual destes não é exemplo de um tipo Referência?
interface
enum
string[]
string
object

R: enum
```

```
Qual destes não é exemplo de um tipo Valor?
class
int
char
c. bool
struct

R: class
```

```
O que é correto afirmar sobre variáveis de tipo Referência?
Variáveis de tipos de referência contêm diretamente seus dados.
A alteração de uma variável de tipo referência não afeta outras que tenham copiado seu valor.
As variáveis de tipo referência têm sua própria cópia dos dados e não é possível que as operações afetem outra variável.
Nenhuma das alternativas.
Variáveis de tipos de referência armazenam referências a seus ponteiros direto na memória.

R: Variáveis de tipos de referência armazenam referências a seus ponteiros direto na memória.
```

```
Quais destes são instruções condicionais?
for e while
try e catch
using e declare
break e continue
if e switch

R: if e switch
```

```
Quais destes são instruções para tratativa de exceções?
using e declare
if e switch
try e catch
for e while
break e continue

R: try e catch
```

```
Qual das inicializações de array a seguir é inválida?
string[] a = new int[] {1, 2, 3};
int[] a = {1, 2, 3};
Todas estão corretas.
int[] a = new int[] {1, 2, 3};
int[] a = new int[10];

R: string[] a = new int[] {1, 2, 3};
```

```
Os índices dos elementos de um array começam a ser contados em:
0
-1
Nenhuma das alternativas.
1
null

R: 0
```

```
O que é correto afirmar sobre variáveis de tipo Valor?
Variáveis de tipos de valor armazenam referências a seus dados.
Nenhuma das alternativas.
Variáveis de tipos de valor contêm diretamente seus dados.
É possível que duas variáveis de tipo valor façam referência ao mesmo objeto.
A alteração de uma variável de tipo valor afeta outras que tenham copiado seu valor.

R: Variáveis de tipos de valor contêm diretamente seus dados.
```

```
Qual das afirmações não é verdadeira sobre Arrays?
Arrays são tipos de valor.
Todos os elementos de um array são do mesmo tipo.
Os elementos de um array são acessados através de índices.
Ao criar um array é especificado o tamanho da nova instância, que é fixo durante todo o tempo de vida da instância.
Um array é um estrutura de dados que contém um número X de elementos.

R: Arrays são tipos de valor.
```

```
Quais destes são instruções de repetição?
break e continue
if e switch
using e declare
try e catch
for e while

R: for e while
```

[Voltar ao Índice](#indice)

---


## <a name="parte5">5 - Classes e objetos essenciais em C#</a>

**O que são Classes e Objetos em C#**

![](mod05/img/obj_1.png)

![](mod05/img/obj_2.png)

![](mod05/img/obj_3.png)

![](mod05/img/obj_4.png)

![](mod05/img/obj_5.png)

![](mod05/img/obj_6.png)

![](mod05/img/obj_7.png)

![](mod05/img/obj_8.png)

![](mod05/img/obj_9.png)


**Como aplicar classes e objetos em projetos**

```csharp
namespace solutions.Heranca
{
    public class Ponto
    {
        public int x, y;
        private int distancia;
        
        public Ponto(int x, int y)
        {
            this.x = x;
            this.y = y;
        }

        protected void CalcularDistancia()
        {
            //Faz alguma coisa...
            CalcularDistancia2();
        }

        private void CalcularDistancia2()
        {
            //Faz alguma coisa...
        }

        public virtual void CalcularDistancia3()
        {
            //Faz alguma coisa...
        }
    }
}
```


```csharp
namespace solutions.Heranca
{
    public class Ponto3D : Ponto
    {
        public int z;
        public Ponto3D(int x, int y, int z) : base(x, y)
        {
            this.z = z;
            CalcularDistancia();
        }

        public static void Calcular()
        {
            //Faz alguma coisa...
        }
        public override void CalcularDistancia3()
        {
            //Faz outra coisa ...
            base.CalcularDistancia3();
        }
    }
}
```


```csharp
namespace solutions.Metodos
{
    public class Ref
    {
        static void Inverter(ref int x, ref int y)
        {
            int temp = x;
            x = y;
            y = temp;
        }

        public static void Inverter()
        {
            int i = 1, j = 2;
            Inverter(ref i, ref j);
            System.Console.WriteLine($"{i} {j}");    // Escreve "2 1"
        }
    }
}
```


```csharp
namespace solutions.Metodos
{
    public class Out
    {
      static void Dividir(int x, int y, out int resultado, out int resto) 
        {
            resultado = x / y;
            resto = x % y;
        }
        
        public static void Dividir() 
        {
            Dividir(10, 3, out int resultado, out int resto);
            System.Console.WriteLine("{0} {1}", resultado, resto);	// Escreve "3 1"
        }
    }
}
```

**Certifique seu conhecimento**

```
Um método internal pode ser acessado por qualquer parte do código. Sobre esta afirmação:
Ela está correta em partes, pois o internal só pode ser acessado por classes do seu próprio assembly.
Nenhuma das alternativas.
Ela está totalmente correta.
Ela está totalmente errada.
Ela estaria correta se estive falando de um método private.

R: Ela está correta em partes, pois o internal só pode ser acessado por classes do seu próprio assembly.
```

```
Sobre métodos estáticos é correto afirmar:
Pertencem a classe e não ao objeto.
Não são visualizados através de uma instância da classe.
São declarados com o modificador "static".
Todas as alternativas estão corretas.
São acessados diretamente pela classe.

R: Todas as alternativas estão corretas.
```

```
Quando a classe A herda da classe B, a classe A herda todos os membros da classe B. Sobre esta afirmação é correto afirmar que:
Nem todos os membros são herdados.
Só serão herdados os membros static.
Só serão herdados os membros protected.
Só serão herdados os membros public.
Só serão herdados os membros private.

R: Nem todos os membros são herdados.
```

```
Uma classe é uma estrutura de dados que combina:
Objetos e memória.
Nenhuma das alternativas.
Ação e reação.
Estado e ações.
Público e privado.

R: Estado e ações.
```

```
Sobre objetos é correto afirmar
A memória ocupada por um objeto é recuperada automaticamente quando o objeto não está mais acessível.
São instâncias de uma classe.
São criados usando o operador new.
Possui membros.
Todas as alternativas estão corretas.

R: Todas as alternativas estão corretas.
```

```
Sobre membros é correto afirmar:
Membros estáticos pertencem a classe e membros de instância pertencem ao objeto.
Todas as alternativas são corretas.
Constantes, variáveis, métodos, propriedades e construtores são exemplos de membros.
Cada membro de uma classe tem uma acessibilidade associada, que controla as regiões do texto do programa que podem acessar o membro.
Os membros de uma classe podem ser estáticos ou membros da instância.

R: Todas as alternativas são corretas.

```

```
Qual dos itens abaixo não representa um tipo de acessibilidade de um membro?
protected
internal
private
public
static

R: static
```

```
O que indica o modificar "ref" antes de um parâmetro em um método?
Indica que aquele parâmetro será passado como referência.
Indica que que o parâmetro não pode ser nulo.
Não indica nada.
Indica que qualquer ação que afete o valor final do parâmetro não será retornada para fora do método.
Nenhuma das alternativas.

R: Indica que aquele parâmetro será passado como referência.
```

```
O que são objetos?
São um membro que implementa uma computação ou ação.
São os tipos mais fundamentais de C#.
São instâncias de uma classe.
São uma estrutura de dados.
Todas as alternativas são corretas.

R: São instâncias de uma classe.

```

```
Sobre métodos é errado afirmar:
Método implementa uma computação ou ação que pode ser executada por um objeto ou classe.
Método é um tipo de membro.
Os métodos podem ter uma lista de parâmetros.
Os métodos não podem ter um tipo de retorno.
Os parâmetros de um método podem ser do tipo valor ou referência.

R: Os métodos não podem ter um tipo de retorno.
```



[Voltar ao Índice](#indice)

---


## <a name="parte6">6 - Trabalhando com structs, interfaces e enums</a>

**O que são Structs**

![](mod06/img/struct_1.png)

![](mod06/img/struct_2.png)

![](mod06/img/struct_3.png)

![](mod06/img/struct_4.png)

![](mod06/img/struct_5.png)

[https://www.eximiaco.tech/pt/category/fundamentos/](https://www.eximiaco.tech/pt/category/fundamentos/)

**Entendendo a função de interfaces e enums**

![](mod06/img/inter_1.png)

![](mod06/img/inter_2.png)

![](mod06/img/inter_3.png)

![](mod06/img/enums_1.png)

![](mod06/img/enums_2.png)

![](mod06/img/enums_3.png)

![](mod06/img/enums_4.png)

![](mod06/img/enums_5.png)

**Certifique seu conhecimento**


```
Um Enum que não declara explicitamente um tipo subjacente tem um tipo subjacente:
sbyte
string
interface
int
object

R: int
```

```
Sobre Enums é correto afirmar:
Eles fornecem significado semântico a valores discretos.
São chamados com o operador new.
São tipo de referência.
Pode conter métodos, propriedades, eventos e indexadores.
Nenhum das alternativas.

R: Eles fornecem significado semântico a valores discretos.
```

```
Qual área da memória que as Classes requerem alocação e as Structs não requerem?
RAM
Flash
Heap
HD
Stack

R: Heap
```

```
Qual das alternativas abaixo não é verdadeira sobre Structs?
Structs não aceitam herança determinada pelo desenvolvedor.
São úteis para pequenas estruturas de dados que possuem semântica de valor.
Uma variável de um tipo de struct armazena diretamente os dados da estrutura.
O uso de structs em vez de classes para pequenas estruturas de dados pode fazer uma grande diferença no número de alocações de memória.
As structs são tipos de valor e requerem alocação de heap.

R: As structs são tipos de valor e requerem alocação de heap.
```

```
Qual o tipo que as Strucuts se enquadram?
Classes.
Nenhuma das alternativas.
Tipo referência.
Tipo valor.
Objetos.

R: Tipo valor.
```

```
O que é uma Interface em C#?
São instâncias de uma classe.
É a tela do Visual Studio Code onde o desenvolvedor escreve o código.
São os tipos mais fundamentais de C#.
Uma interface define um contrato que pode ser implementado por classes e structs.
Nenhuma das alternativas.

R: Uma interface define um contrato que pode ser implementado por classes e structs.

```

```
O que é um Enum no C#?
É um tipo de valor distinto com um conjunto de constantes nomeadas.
São os tipos mais fundamentais de C#.
Nenhum das alternativas.
Um contrato que pode ser implementado por classes e structs.
É um tipo abstrata para inteiros.

R: É um tipo de valor distinto com um conjunto de constantes nomeadas.

```

```
O que são Structs?
São instâncias de uma classe.
São os tipos mais fundamentais de C#.
Nenhuma das alternativas.
São estruturas de dados que podem conter membros de dados e membros de ação.
São um contrato que pode ser implementado por classes.

R: São estruturas de dados que podem conter membros de dados e membros de ação.

```

```
Sobre Interface é correto afirmar:
Todas as afirmativas estão corretas.
As interfaces podem empregar herança múltipla.
Uma interface pode conter métodos, propriedades, eventos e indexadores.
Uma interface define um contrato que pode ser implementado por classes e structs.
Uma interface não fornece implementações dos membros que define - apenas suas “assinaturas”;

R: Todas as afirmativas estão corretas.
```

```
Qual área da memória que normalmente as Structs são alocadas?
Stack
Flash
HD
RAM
Heap

R: Stack
```

[Voltar ao Índice](#indice)

---


## <a name="parte7">7 - Uma síntese do que é .NET</a>

**Revisão introdutória**

**Praticando primeiros passos**


**Dinâmica de desenvolvimento**


**Considerações finais**

[mod07fim\solutions](mod07fim/solutions)

[Voltar ao Índice](#indice)

---

