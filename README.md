Esse é o projeto de entrega do desafio de Rasomware da DIO

Após realizar o fork no repositório

Baixe os arquivos no seu Kali Linux

Caso tenha baixado o ".zip"  descompacte ele

Abra o terminal linux

Navegue até a pasta dos arquibos "cibersecurity-desafio-ransomware-master"

Liste os arquivos da pasta para ver que estão lá.

Abra o arquivo de texto no editor "nano teste.txt" e digite algum texto

Execute novamente o python de encriptação "python encrypter.py"

  * No meu caso não tinha a biblioteca PYAES instalada no meu Kali

  * Nesse caso precisei baixar a biblioteca

  * executei o comando de "sudo apt-get -y install python3-pyaes"

Execute novamente o python de encriptação "python encrypter.py"

Liste os arquivos da pasta e verifique que agora há um novo arquivo "teste.txt.ransomwaretroll"

Abra o arquivo "nano teste.txt.ransomwaretroll"

Veja que agora o texto foi encriptado

Execute o arquivo python de decriptação "python decrypter.py"

Liste os arquivos da pasta e verifique arquivo "teste.txt"

Abra o arquivo "nano teste.txt"

Agora é só verificar se o conteúdo que você escreveu está lá.
