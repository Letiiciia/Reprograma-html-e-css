### exercicio1-Reprograma
# HTML

![download](https://github.com/Letiiciia/exercicio1-reprograma/blob/master/download.png)

É a linguagem base dos websites

Camadas de desenvolvimento:
Existem 3 linguagens básicas que utilizamos para criar websites: HTML, CSS e JavaScript.
O HTML é a linguagem que irá exibir a informação. O CSS é a linguagem que vai deixar essa informação bonitona. O JavaScript é a linguagem que vai fazer essa informação receber alguns comportamentos, como por exemplo ao criar um submenu ou controlar algo que aparece e desaparece na tela.

O HTML sem dúvida é a mais importante de todas, por que como dissemos no começo, é ela que exibe a informação. Além de exibir a informação, ela dá significado. Isso é importante por que alguns sistemas como o Google, que irão ler sua página, precisam entender o que é cada elemento nela e o que cada um desses elementos significam.

# O nome HTML

O acrônico HTML significa em inglês: HyperText Markup Language. Para gente aqui fica: Linguagem de Marcação de Hipertexto. Bonito, né?
Por trás das palavras Hipertexto e Marcação tem muita história e guardam a real essência da função do HTML. 
Se você tiver que guardar alguma coisa sobre o que é HTML, guarde isso: HTML serve para dar significado e organizar a informação dos websites.


Marcação
Já que o HTML serve para dar significado para a informação, como ele faz isso? Simples: ele marca a informação com as tags.

Por exemplo, para falarmos que um título é um título colocamos um pedaço de texto entre uma tag chamada H1. Veja o código abaixo:

<h1>Aqui vai o texto que é um título</h1>
E dessa forma vamos fazendo todos os outros elementos. Um parágrafo, por exemplo:

<p>Aqui vai muito texto, um parágrafo</p>
O resultado fica assim:

Aqui vai o texto que é um título
Aqui vai muito texto, um parágrafo

# Estrutura básica

Iniciando o código básico de HTML
O documento HTML sempre inicia com o que chamamos de estrutura básica. Esta estrutura é quase que imutável. Sempre será dessa forma e você sempre, sempre começará seu HTML começando por esse código. Geralmente os editores como o Sublime Text já tem atalhos para iniciar os documentos HTMLs com essa estrutura, logo, você não precisa se preocupar em decorá-la, mas é bom que faça. Veja abaixo como ela se inicia:

<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title>Título da página</title>
    <meta charset="utf-8">
  </head>
  <body>
    Aqui vai o código HTML que fará seu site aparecer.
  </body>
</html>
É possível compreender o documento em HTML de uma maneira muito simples, através de uma divisão de blocos das tags essenciais, conforme a a seguinte estrutura:

Definição do documento (doctype)
Cabeça (head)
Corpo (body)
Doctype - Definindo o documento
Uma coisa importante: SEMPRE deve existir o doctype, que é este código <!DOCTYPE html>.

O doctype não é uma tag HTML, mas uma instrução para o navegador e outros programas que podem ler seu site, que o código encontrado ali é um código HTML. Assim eles sabem o que fazer para mostrar seu site da melhor forma possível. Lembre-se: o doctype é OBRIGATÓRIO e deve ser sempre a PRIMEIRA LINHA do seu documento.

HEAD
Contém informações que não são transpostas visivelmente para o usuário/leitor do documento. São dados implícitos, de uso e controle do documento: vinculação com outros arquivos, aplicação de lógica de programação de scripts e metadados. Na prática, todo o conteúdo do cabeçalho fica delimitado entre a abertura e fechamento tag head.

BODY
Trata-se do documento em si, ou seja, a informação legível para o usuário/leitor do documento. É todo e qualquer texto que se deseja apresentar, assim como toda e qualquer forma de mídia de saída (imagens, sons, miniaplicativos embutidos, conteúdo multimídia, etc). Além disso, toda a apresentação de entrada de dados (formulários) também se aplica neste seção do documento. Na prática, o corpo do documento é delimitado pelo par de tags <body> e </body>.

Este é o preceito básico que deve estar muito bem claro para você: onde as marcações se aplicam, e quais são os resultados deste modelo. Por exemplo: se vocês deseja informar conteúdo textual para saída legível ao usuário do seu sistema web, esta marcação deverá obrigatoriamente estar no bloco do corpo da página. Ainda: para definir qual o tipo de codificação da página (uma meta informação do documento), esta deve obrigatoriamente estar marcada no cabeçalho do mesmo documento.

Dentro do elemento BODY sua estrutura de página terá os elementos semânticos da construção da sua página, onde serão declarados e identificados cabeçalhos, rodapé, conteúdo principal, etc.
