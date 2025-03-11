.......................................Linux.......................................

Se não quiser ficar sem proteção (desenvolvedor não especificado) (Ubuntu):


Clica com o botão direito no arquivo e vai em "Propriedades".
Vai na aba "Permissões" e marca a caixa ao lado de "Permitir execução do arquivo como um programa".


Se o launcher não iniciou ou deu erro:


Instala o Java: sudo apt-get install openjdk-8-jre
Depois instala o JavaFX: sudo apt-get install openjfx

(Se tiver Java 9 ou 10, precisa instalar o Java 8 e rodar o launcher com ele,

ou remover completamente o Java 9 ou 10.)


Importante! Recomendamos rodar como root, porque se rodar sem permissões de root,

pode dar problema com os gráficos (gpu).

Roda assim:


Navega até a pasta do cliente com o comando cd
Executa: sudo java -jar TLauncher.jar


.......................................Arch Linux.......................................

Atualiza o sistema: sudo pacman -Suuy
Instala os pacotes: sudo pacman -S jdk8-openjdk jre8-openjdk jre8-openjdk-headless


.......................................Debian/Mint.......................................

Atualiza o sistema: sudo apt-get update, depois sudo apt-get upgrade
Instala os pacotes: sudo apt install default-jdk


.......................................Fedora/CentOS.......................................

Atualiza o sistema: sudo yum update
Instala os pacotes: sudo yum install java-11-openjdk
Executa o comando: sudo update-alternatives --config java e escolhe o número correspondente à versão do Java 11 pra definir como padrão.


.......................................MacOS.......................................

Se não quiser rodar por causa da proteção (desenvolvedor não identificado):


Abre "Ajustes" e vai em "Segurança" (aba Geral).
Clica em "Confirmar abertura". O launcher vai abrir!


Se o launcher não iniciou ou deu erro:


Instala o Java de novo baixando o instalador do site oficial: https://java.com/

(Se tiver Java 9 ou 10, precisa instalar o Java 8 e rodar o launcher com ele,

ou remover completamente o Java 9 ou 10.)
