### exercicio1-Reprograma
# HTML

![download](https://github.com/Letiiciia/exercicio1-reprograma/blob/master/Img/download.png)

<h1>É a linguagem base dos websites</h1>

<p>O HTML é a linguagem que irá exibir a informação. Além de exibir a informação, ela dá significado. Isso é importante por que alguns sistemas como o Google, que irão ler sua página, precisam entender o que é cada elemento nela e o que cada um desses elementos significam.</p>


# O nome HTML

<p>O acrônico HTML significa em inglês: HyperText Markup Language. Para gente aqui fica: Linguagem de Marcação de Hipertexto. Bonito, né?
Por trás das palavras Hipertexto e Marcação tem muita história e guardam a real essência da função do HTML. 
Se você tiver que guardar alguma coisa sobre o que é HTML, guarde isso: HTML serve para dar significado e organizar a informação dos websites.</p>


Marcação
Já que o HTML serve para dar significado para a informação, como ele faz isso? Simples: ele marca a informação com as tags.

Por exemplo, para falarmos que um título é um título colocamos um pedaço de texto entre uma tag chamada H1. Veja o código abaixo:

<h1>Aqui vai o texto que é um título</h1>
E dessa forma vamos fazendo todos os outros elementos. Um parágrafo, por exemplo:

<p>Aqui vai muito texto, um parágrafo</p>
O resultado fica assim:

Aqui vai o texto que é um título
Aqui vai muito texto, um parágrafo

Fonte:https://tableless.github.io/iniciantes/manual/html/index.html

<p>

# Estrutura básica

![images](https://github.com/Letiiciia/exercicio1-reprograma/blob/master/Img/images.png)

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

Fonte:https://tableless.github.io/iniciantes/manual/html/estruturabasica.html

# O que é CSS?

![download](https://github.com/Letiiciia/exercicio1-reprograma/blob/master/Img/download.jpg)

O Cascading Style Sheets (CSS) é uma linguagem utilizada para definir a apresentação (aparência) de documentos que adotam para o seu desenvolvimento linguagens de marcação (como XML, HTML e XHTML e etc..). O CSS define como serão exibidos os elementos contidos no código de um documento e sua maior vantagem é efetuar a separação entre o formato e o conteúdo de um documento.

Por que o CSS foi criado?
Com a evolução dos recursos de programação, as tecnologias estavam adotando cada vez mais estilos e variações para deixá-las mais elegantes e atrativas para os usuários. Com isto, linguagens de marcação simples como o HTML, que era destinada para apresentar os conteúdos, também precisaram ser aprimoradas.

Foram criadas novas tags e atributos de estilo para o HTML e em resumo, ele passou a exercer tanto a função de estruturar o conteúdo quanto de apresentá-lo para o usuário final. Entretanto, isto começou a trazer um problema para os desenvolvedores, pois não havia uma forma de definir, por exemplo, um padrão para todos os cabeçalhos ou conteúdos em diversas páginas. Ou seja, as alterações teriam que ser feitas manualmente, uma a uma.

A partir destas complicações, nasceu o CSS. Primariamente, foi desenvolvido para habilitar a separação do conteúdo e formato de um documento (na linguagem de formatação utilizada) de sua apresentação, incluindo elementos como cores, formatos de fontes e layout. Esta separação proporcionou uma maior flexibilidade e controle na especificação de como as características serão exibidas, permitiu um compartilhamento de formato e reduziu a repetição no conteúdo estrutural de um documento.

Com isto, as linguagens de marcação passaram novamente a exercer sua função de marcar e estruturar o conteúdo de um documento, enquanto o CSS encarregou-se da aplicação dos estilos necessários para a aparência dela. Isto é feito por meio da criação de um arquivo externo que contém todas as regras aplicadas e com isto, é possível fazer alterações de estilo em todas as páginas de um site e outros documentos que utilizam CSS de forma fácil e rápida.

O CSS também permite que as mesmas marcações de um documento sejam apresentadas em diferentes estilos, conforme os métodos de renderização (como em uma tela, impressão, via voz, baseadas em dispositivos táteis, etc.). A maioria dos menus em cascata, estilos de cabeçalho e rodapé de páginas da internet, por exemplo, atualmente são desenvolvidos em CSS.

Fonte:https://tableless.github.io/iniciantes/manual/css/

