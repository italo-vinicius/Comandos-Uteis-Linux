# Comandos-Uteis-Linux
Alguns comandos uteis para Linux


```ls => retorna a lista de diretórios presentes no diretório atual

man ls => o 'man' retorna um manual de como funciona o comando ls(ou qualquer outro descrito junto ao 'man')

ls --help => o help mostra um resumo da funcionalidade do ls(ou qualquer outro comando)

clear => limpa o terminal(pode usar control + L tambem)

mkdir name => cria um diretório(substitua o name pelo nome do diretório). Caso queira criar mais de um diretório, 
posso passar outros parametros como argumentos(Ex: mkdir pasta1 pasta2 pasta3).E caso queira criar apenas um diretório com um nome composto, basta colocar aspas no nome.

cd nameDirectory => muda de diretório

cd .. => sobe um nivel de diretório

pwd => imprime o diretório em que você se encontra atualmente

whoami => imprime o usuário atual

whoami >> name.txt => O '>>' joga as informações que serão retornadas pelo comando whoami(ou qualquer outro) e grava em um arquivo txt

touch name.txt => cria um arquivo txt

nano nameFile.txt => edita o arquivo txt 

cat nameFile.txt => Abre o arquivo txt no terminal para leitura

mv oldName newName => modifica o nome do arquivo ou diretório

cp nameFile /home/italo/pastaTeste => copia o arquivo para pastaTeste

find . -name nameFile.txt => Tenta encontrar o arquivo nameFile em todos os diretórios presentes abaixo do 
diretório atual. Caso queira uma busca mais ampla, pode usar apenas *txt*(ou qualquer outra extensão) e ele encontrará tudo que tiver txt 

rm nameFIle.txt => remove o arquivo txt..esse comando não remove diretórios

rmdir nameDirectory => Agora sim, conseguimos remover um diretório vazio com o 'rmdir'

rm -rf nameDirectory => REMOVE todo os arquivos na pasta descrita..TUDO

hostname => mostra o nome do host

hostname -I => retorna o IP

free -h => traz informações do uso da memória do pc

htop => mostra informações do pc, mas de uma maneira mais 'suave' de se ver

df -h => informa o armazenamento do seu Pc

ncdu => escaneia todos os diretórios do pc e ordena as pastas por tamanho de uso de armazenamento

history => retorna todos os comandos que você usou no terminal

```
