#Folha de Estilo

Este documento cont�m informa��es sobre os padr�es de estilo de escrita e organiza��o do livro colaborativo.

## Regionaliza��o

O livro est� escrito em l�ngua portuguesa.

## Equa��es e s�mbolos matem�ticos

As equa��es e s�mbolos matem�ticos est�o escritos usando a cole��o de pacotes [AMS-LaTeX](http://www.ams.org/publications/authors/tex/amslatex). Para mais informa��es, recomendamos a leitura do seguinte documento:

ftp://ftp.ams.org/pub/tex/doc/amsmath/short-math-guide.pdf

## Organiza��o do c�digo fonte

O livro est� escrito em [LaTex](https://latex-project.org/). O arquivo principal (`main.pdf`) escontra-se no diret�rio principal (`CalculoNumerico`). O c�digo LaTeX de cada cap�tulo encontra-se em um subdiret�rio espec�fico com nome `cap_abrev`, onde `abrev` � uma abrevia��o que lembre o conte�do do cap�tulo. Por exemplo, o c�digo do cap�tulo sobre t�cnicas num�ricas para sistemas lineares est� no subdiret�rio `cap_linsis`.

### Cap�tulos

Dentro de cada subdiret�rio de um cap�tulo, por exemplo, `cap_foo` devem estar presentes todos os arquivos referentes ao texto deste. As imagens devem ser colocadas em no subdiret�rio `cap_foo/pics` e os c�digos computacionais em `cap_foo/codes`.

