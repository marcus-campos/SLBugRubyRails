No Windows:

Tente atualizar seus certificados SSL.

Baixe http://curl.haxx.se/ca/cacert.pem .

Salve este arquivo em qualquer lugar que quiser, tais como:

C:\RailsInstaller\cacert.pem
Na linha de comando, diga ao Ruby onde encontrar o arquivo cert:

set SSL_CERT_FILE=C:\RailsInstaller\cacert.pem

Tente novamente a instala��o pelo GEM.

Se funcionar, isso � �timo. Se voc� quiser que isso funcione com todos os projetos em seu sistema, e tamb�m sobreviver a reinicializa��o, ent�o voc� pode fazer o arquivo cert permanente , adicionando a todo o sistema cert. 
Para fazer isso , use o painel de controle do Windows.

Creditos (http://stackoverflow.com/questions/27584830/setting-up-rails-server)