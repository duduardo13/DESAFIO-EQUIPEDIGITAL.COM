# DESAFIO-EQUIPEDIGITAL.COM

## Introdução.

Olá, esse é o projeto no qual fui desafiado pela EquipeDigital.com

Consiste basicamente em realizar uma cópia do site https://2030today.com.br/ utilizando Wordpress. Aqui ensinarei como montar o setup para que o projeto possa funcionar em sua máquina:

## Instalando o projeto.

Primeiramente iremos baixar o servidor que irá permitir que o site funcione, para isso estarei anexando abaixo o link de download da aplicação + link de um video explicativo para auxiliar na instalação (siga fielmente os passos do vídeo para não encontrar dificuldades na instalação):


- Download XAMPP: https://www.apachefriends.org/pt_br/index.html

- Tutorial de instalação e configuração inicial: https://youtu.be/d_91AknqKeE?si=OQ-YAj_HSoDBolds

OBS: A instalação do XAMPP se estende até os 5:30min de vídeo, após finalizar a instalação seguir com os próximos passos descritos abaixo.


Após instalar o XAMPP, iremos baixar os arquivos do site nesse link (baixe os arquivos 2030today.zip e 127_0_0_1.sql):  https://drive.google.com/file/d/1CZeMhDkZyvcDVowHp_jZDUxO_Lnh4wHo/view?usp=drive_link

Após descarregar os arquivos, você irá precisar descompactar o arquio 2030today.zip em uma pasta chamada "htdocs" e para localiza-la, deverá procurar pelo diretório no qual instalou a aplicação XAMPP e buscar pela pasta "xampp" e em seguida buscar pela "htdocs".

Abra o XAMPP e clique botão "Start" nas opções APACHE e MYSQL, depois em seu navegador de preferência, digite na url "localhost/phpmyadmin" e siga os seguintes passos:

- Procure pela opção "novo" no menu lateral esquerdo;
- No campo escrito "Nome do banco de dados" escreva "2030todaywp" e clique em Criar;
- Selecione no menu lateral o banco de dados que criou e no menu superior busque pela opção "Importar" e selecione;
- Busque pela opção de selecionar ficheiro, selecione o arquivo 127_0_0_1.sql disponibilizado anteriormente para download e clique em importar.


## Executando o projeto.

Se tudo ocorreu bem, abra o navegador de sua preferência e digite na url:

- Para visualizar o projeto: localhost/2030today

- Para acessar o painel que permite realizar modificaçãoes do projeto (Usuário: eduardo, Senha: 123456): localhost/2030today/wp-admin/


