# Curso Balta   : https://balta.io/carreiras/dotnet-fundamentals

Esses são os meus estudos de C# pelo curso da Balta, antes  de seguir com o roadmap principal de ASP.NET Core. Fui anotando aqui o que fui aprendendo.

## O que é C#
C# é uma linguagem da Microsoft, fortemente tipada, compilada, gerenciada e orientada a objetos. Roda em cima do .NET e do CLR. SOMENTE GRANDES EMPRESAS UTILIZAM 

O fluxo até o código rodar é mais ou menos assim:
C# → IL → CLR/JIT → código de máquina → execução


## Fundamentos que fui praticando

- Var.cs = declarando variáveis com `var` (idade, nome, peso) e jogando no console.
- Const.cs =  testei um pouco de `const` (deixei uns exemplos comentados) e usei `var` pra guardar texto.
- Boleano.cs = só declarando variáveis `bool` mesmo, pra entender o tipo.

## Calculadora

Dentro da pasta `Calculadora/` fiz uma calculadora de console pra treinar. Ela tem um menu com switch que deixa escolher entre soma, subtração, divisão e multiplicação, lê os valores digitados com `Console.ReadLine()` + `float.Parse` e mostra o resultado usando interpolação de string. Depois de cada conta ela volta pro menu de novo.

## Editor HTML (console)

Fica na pasta `Editor.cs/` e simula um mini editor/visualizador de texto com marcação parecida com HTML:

- Program.cs só chama o menu.
- Menu.cs desenha a "tela" no console (aquelas bordas com `+`, `-` e `|`) e deixa escolher entre criar um arquivo novo ou abrir um.
- Editor.cs é o modo de escrever: vai lendo linha por linha até eu apertar `Esc`, guardando tudo num `StringBuilder`.
- Viewer.cs é o modo de visualizar: usa Regex pra achar as tags `<strong>` no texto e pinta essas palavras de azul no console, como se fosse uma renderização bem simples de HTML.

Nesse projeto acabei praticando várias coisas juntas: namespace, classe estática, StringBuilder, cor no console, `SetCursorPosition` e um pouco de Regex.


