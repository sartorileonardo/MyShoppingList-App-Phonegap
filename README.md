# MyShoppingList-App-Phonegap
Projeto de lista de comprar com função de Add/Remove para dispositivos móveis.

Apache Cordova é um framework de desenvolvimento móvel de código aberto. Ele permite você usar tecnologias web padrão - HTML5, CSS3 e JavaScript para o desenvolvimento multi-plataforma. Os aplicativos são executados dentro de containers direcionados para cada plataforma, e contam com ligações API padrões compatíveis para acessar os recursos de cada dispositivo, tais como sensores, dados, status da rede, entre outros de acordo com Foundation (2015).

Este framework é recomendado quando um desenvolvedor tem os seguintes objetivos para com sua aplicação:

• Criar um aplicativo mobile compatível com diversas plataformas, sem precisar criar um
aplicativo codificado com a linguagem de programação nativa de cada plataforma, exemplo: Android, IOs, Windows Phone.

• Disponibilizar sua aplicação em várias lojas web de aplicativos, exemplo: Google Play, Apple Store, etc.

• Utilizar uma mistura de componentes nativos da plataforma com componentes WebView (janela do navegador de internet), ou desenvolver algum plug-in para comunicação destes componentes.

Aplicativos que usam o PhoneGap se tornam aplicativos compatíveis com a plataforma e SDKs desejada, e pode ser disponibilizado para instalação de loja de cada smartphone. Ao usar as APIs do PhoneGap, um aplicativo pode ser construído sem qualquer código nativo (Java, Objective-C, C#, entre outros) da plataforma a ser disponibilizado o software. Em vez disso, tecnologias Web são utilizadas, e eles são hospedados no próprio dispositivo localmente, o código é compilado junto ao código nativo, dispensando a necessidade de um servidor HTTP remoto para hospedar o código web, segundo Júnior, OLIVEIRA e JÙNIOR (2015).


De acordo com Foundation (2015, tradução nossa), Um aplicativo codificado utilizando a plataforma Apache Cordova raramente será tão rápido quanto um aplicativo codificado em linguagem nativa da plataforma do dispositivo móvel, uma vez que o código nativo tem acesso direto ao hardware do dispositivo. Além disso, um aplicativo híbrido ou web mobile nem sempre poderá utilizar do uso de todos os recursos de hardware do dispositivo móvel, como por exemplo: câmera, acelerômetro, entre outros, pois para utilizar desses recursos é preciso utilizar-se de plug-ins que fazem a ponte de comunicação, que podem ou não ser encontrados dependendo de sua especificidade.

Nesse laboratório/repositório segue o código de uma Lista de Compras com as funções de Add/Remove.

Este laboratório é de nível básico, integrando as tecnologias dos frameworks Phonegap e AngularJS.

Para instalar o framework Phonegap/Apache Cordova, segue o comando referente ao terminal Linux:
####################################################################
#NodeJS
curl -sL https://deb.nodesource.com/setup_7.x | sudo -E bash - ;
sudo apt-get install -y nodejs ;

#Apache Cordova
sudo npm install -g cordova ;
sudo apt-get install ia32-libs ;

#Phonegap
sudo npm install -g phonegap ;
####################################################################

Segue os comandos abaixo para desdenvolvimento do projeto:
Obs1: ao executar "phonegap serve" o App já está disponível para acessar no browser do dispositivo mobile ou notebook.
Obs2: após criar os projetos, os comandos devem ser executados dentro do diretório do projeto.

Segue a lista de comandos para executar no terminal Linux:

1- Criando projeto:
phonegap create PhonegapProject io.phonegap.hello PhonegapApp

2- Adicionando Plataforma:
phonegap platform add android
phonegap platform add ios
phonegap platform add windows

3- Disponibilizar serviço
phonegap serve


REFERÊNCIAS:

FOUNDATION, T. A. S. Cordova Documentation. 2015. Cordova Documentation. Disponível em: <https://cordova.apache.org/docs/en/latest/guide/overview/index.html>. Acesso em: 13 jul. 2016.


JÚNIOR, G. d. P. S.; OLIVEIRA, A. C.; JÙNIOR, E. A. L. Aplicação multiplataforma da realidade aumentada móvel para geolocalização utilizando o phonegap. Programa de Pós-Graduação em Engenharia Elétrica. Universidade Federal de Uberlância. Uberlândia/MG, sd, 2015. .

