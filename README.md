Gtalk -> Twitter
=============================

Este exemplo mostra como usar o Gtalk para mandar mensagens para o Twitter.

Voc� precisa configurar:

* O arquivo app.properties (dentro de src/main/resources)
* Maven

Voc� N�O precisa configurar:

* Um application server
* O arquivo applicationContext.xml (embora voc� possa, caso exista algo que voc� queira modificar)

Como usar: v� at� a raiz do projeto e digite mvn exec:java. Cuidado: assim que estiver pronto, ele vai mandar uma mensagem para voc� que ser� automaticamente tuitada. Se quiser alterar isso, edite o arquivo applicationContext.xml (que est� presente em src/main/resources).