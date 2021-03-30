##Git hub conection##

Estabelecendo conexão com Github toda vez que reiniciar R studio ou Git Bash (se quiser modificar os aquivos que estão lá)

Comandos no Terminal
##pode estar dentro da pasta já ou no home~

##conectar com agent
#$ eval "$(ssh-agent -s)"


##adicionar chave
#$ ssh-add ~/id_rsa.pub
#Enter passphrase: isbl00

##verificar conexão
#$ ssh -T git@github.com
#Hi itpereira!

##puxar as atualizações dos arquivos do Github (dentro da pasta de interesse)
#$ cd JRclass2/
#$ git pull

###Criando e enviando arquivos

##criar um arquivo
#$ nano Github_conection.md    >>> nano ferramenta edição texto; .md arquivo leitura Markdown
#escrever o que quiser, salvar, ele é criado na pasta

##adicionar ao git
#$ git add Github_conection.md

##commit ao git (adicionar comentarios de edição)
#$ git commit -am "instruçoes"

##enviar ao github
#$ git push

###theEND
