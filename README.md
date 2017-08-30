Fala DevOpeiros!

Agora é hora de começar a testar seus conhecimentos, aqui estão os exercícios sobre LINUX! Aproveite e divirta-se!

1- Instalar o Debian, Ubuntu ou CentOS seguindo o seguinte particionamento:
/  ext4 4gb
/home xfs 1gb
/usr ext4 2gb
/home ext4 1gb
swap 512mb

Evidencias imagens Exec 1a e Exec 1b


2- Realizar a instalação dos seguintes pacotes:
- bb
- apache
- python3
- pip
- git

Evidencias imagen Exec 2

3- Mudar a qtde de comandos que o history retorna para 10, essa mudança tem que ser definitiva e não somente na sessão atual.

Evidencias imagen Exec 3

4- Criar um alias para que retorne a saída do comando "ps -ef” chamado lista_processos, lembre-se, de forma definitiva e não somente na sessão atual.

Evidencias imagen Exec 4

5- Realizar o upgrade de todos os pacotes.

Evidencias imagen Exec 5

6- Crie um arquivo e modifique a permissão para - rwx r-x r-x utilizando o modo octal.

Evidencias imagen Exec 6

7- Crie um arquivo e modifique a permissão para -r-xr—r-- utilizando o modo simbolico.

Evidencias imagen Exec 7

8- Crie um usuário sem utilizar o comando useradd ou adduser, aqui você terá que criá-lo adicionado toda info necessária diretamente no arquivo responsável e terá que criar os diretórios necessários manualmente.

Evidencias imagen Exec 8
Foi necessário adicionar uma linha no /etc/passwd, depois rodei passwd para o usuário luishpd adicionei a senha, criei o /home/luishpd, conforme havia adicionado a linha, ao logar ele reclamou do grupo 1001, adicionei no /etc/group e ai foi possível logar ser erros.
