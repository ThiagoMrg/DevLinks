# ShortHand

Método para reduzir linhas de códigos.
Objetivo é ter um código mais limpo.

Exemplo de ShortHand

background: url(./assets/bg\ -\ Mobile.jpg);
background-repeat: no-repeat;  
 background-position: top center;  
 background-size: cover;

Explorando o ShortHand o código ficará assim :
background: color image repeat position/size... etc.
background: url(./assets/bg\ -\ Mobile.jpg) no-repeat top center/cover

# Propriedades do Background

Para fazer a centralização de uma imagem, por exemplo, podemos utilizar "background-position: center;".
Porém, essa propriedade faz com o seja centralizado o eixo X do elemento. Então é possível que se pegarmos uma imagem retangular de bg e aplicarmos o "background-position: center;" a imagem fique quadrada. Uma solução para isso é acrescentar o ''top''... "background-position: top center;"

## Background-size

background-size: cover; O Cover vai cobrir todo espaço da tela.

background-size: contain; O contain é parecido, mas precisaria definir a largura e a altura para ele ''conter'' dentro do espaço definido.

# Anotações CSS
Geralmente não precisa definir altura no CSS.
Geralmente a altura segue o conteúdo da página. Assim fica uma página mais fluída.

## margin: auto;
Não é possível aplicar em elementos inline; 
Usado para centralizar elementos no exixo X.  
