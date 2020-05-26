# Exemplo AES (em Java e Python)

Este repositório foi criado originalmente para conter os arquivos fonte para a classe no vídeo do [YouTube](https://youtu.be/2cef8T-NZDk).
Contudo um [novo vídeo foi feito demonstrando o mesmo exemplo em Python](https://youtu.be/YwaRKApoGDc).

## Em Java

O exemplo em Java foi construido utilizando NetBeans, portanto você irá precisar instalá-lo para compilar o exemplo.
Ele irá criar os arquivos compilados .class no subdiretório __build__.
Para executar a classe de exemplo na linha de comando

```
cd build\classes
java com.blogspot.h3dema.ExemploAES
```

Isto irá gerar a saída

> Texto original:
> aqui colocaremos o texto criptografado AES
> Texto (hexa):6171756920636F6C6F636172656D6F73206F20746578746F2063726970746F6772616661646F204145530A0A0A0A0A0A0A0A0A0A
> Cipher:7C5FF01AFAAC5A0F33E1638DB7933CFD63F4F55F7A5C7241D8EA4D5C5D8B51283C98A5F0B3C9BC9DBDAC4DB6BBC1141481A84A7E
> Mensagem:6171756920636F6C6F636172656D6F73206F20746578746F2063726970746F6772616661646F204145530A0A0A0A0A0A0A0A0A0A

## Em Python

O exemplo em Python utiliza um ambiente de desenvolvimento denominado [Jupyter](https://jupyter.org/install) com Python versão 3.
O notebook com o código está no folder "Python", dentro deste repositório.

