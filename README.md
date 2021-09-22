# Nome do usuário -> logado no ->SO(nome editável)
gabriel@ubuntu:~$ 

# Significa home (pode combar com o CD)
~

# Nome do usuário (quem sou eu)
whoami

# Modo de usuário normal
gabriel@ubuntu:~$

# Modo de usuário Root
gabriel@ubuntu:~#

# Limpar tela
CTRL + L
clear

# Listagem no diretório atual
ls

# Listagem com estrutura de permissões
ls -l

# Listagem de arquivos ocultos
ls -A

# Remover diretório vazio
rmdir

# Remover qualquer coisa
rm

# Remover qualquer coisa recrusiva
rm -r 

# Entrar em pasta com espaço
'Minha Pasta Home'
cd 'Minha Pasta Home'
cd Minha\ Pasta\ Home

# printar diretorio de trabalho atual
PWD

# Criar arquivo qualquer
touch file.txt

# Consultar o manual
man ls

# Ver menu de ajuda de um comando
ls --help

> Super usuário faça => Faça isso como super usuário
> APT - Advanced Package Tool

# Atualiza o ?? sistema ??
sudo apt-get update

# Ver pacotes que podem ser atualizada
apt list --upgradable

# Listar pacotes com um determinado nome (repositório web)
apt list gimp

# Pesquisar pacotes com um determinado nome (repositório web)
apt search freecad

# Instalar pacote
sudo apt install freecad

# Remover pacote não usados mais
sudo apt autoremove

# Remover pacote
sudo apt remove freecad

# Instalar pacotes sugeridos, atualizar existenstes
sudo apt upgrade

# Além de atualizar, também remove pacotes que os devs não querem mais
sudo apt full-upgrade

# Além de atualizar, também remove pacotes que os devs não querem mais
sudo apt dist-upgrade

# Ver informações do pacote
apt show gimp

# Ver dependencias do pacote
apt-cache depends freecad

# Instalar pacotes deb
sudo dpkg -i file.deb

# Local onde construi pacotes e armazena gratuitamente
lauchpad ppa
Adiciona na lista de pacotes
Combado com um update instala o pacote












