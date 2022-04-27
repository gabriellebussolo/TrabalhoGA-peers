## Trabalho Prático - Peers
 
O Trabalho Prático - Peers, consiste no primeiro trabalho da disciplina de Redes de Computadores I. Nele, foi criado um software de terminal distribuído com três peers.
Cada peer possui função de servidor e de cliente. Além disso, há um servidor centralizado, no qual será utilizado para ter um controle dos peers conectados.

<p align="center">
 <a href="#tecnologias">Tecnologias</a> •
 <a href="#serviços-usados">Serviços usados</a> • 
 <a href="#preparando-o-container">Preparando o container</a> • 
 <a href="#executando-o-projeto">Executando o projeto</a> • 
 <a href="#features">Features</a> • 
 <a href="#licenc-a">Licença</a> • 
 <a href="#autora">Autora</a>
</p>
 
## Tecnologias 
  
* Python version  3.10.4
 
## Serviços usados
 
* Github
* Oracle VM Virtual Box version 6.1.26
* Docker Desktop 4.7.1
 
## Preparando o container
 
* Para criar um container e entrar no seu terminal:
>    $ docker container run -it gcc bash
* Para enviar os arquivos do projeto da sua máquina para os containers (caso esteja utilizando Windows), abra outro PowerShell e entre no diretório onde estão os arquivos desse projeto. Lá, execute o seguinte comando, substituindo 'containerid' pela id do container de destino:
>    $ docker cp .\peer.py containerid:/home/
 
## Executando o projeto

Para executar esse projeto, é necessário seguir os seguintes passos:

* Em um terminal, execute o código 'servidor.py':
>    $ python3 servidor.py

* Em outros três terminais, execute o código 'peer.py':
>    $ python3 peer.py
 
## Features
 
* Envio de um comando em um peer para os outros peers
* Execução dos comandos em cada peer
* Coleta e envio da resposta do comando para o peer de origem do comando
* Apresentação dos retornos do comando de cada peer, no peer de origem do comando
 
## Autora
 
* **Gabrielle Bussolo**: @gabriellebussolo (https://github.com/gabriellebussolo)
