Tarefa de Programação Streaming de Vídeo
======


Introdução
----
Tarefa de Programação referente ao Capítulo de Redes Multimídia. Neste laboratório, o alunoimplementará um servidor de streaming vídeo e um cliente que se comunicamusando  o  protocolo  de  fluxo  contínuo  em  tempo  real  (RTSP)](https://www.ietf.org/rfc/rfc2326.txt)  e  envia  dados  usando  o protocolo de tempo real (RTP)]((https://en.wikipedia.org/wiki/Real-time_Transport_Protocol). O objetivo é implementar o protocolo RTSP no cliente e implementar o empacotamento RTP no servidor.



Executar Cliente/Servidor
----
Primeiramente, compile all `*.java` ou digite o comando `$ make`.

AApós compilar, basta executar os comandos:

```
$ java Server [port]
$ java Client [host] [port] [FILE]
```

Exemplo:

```
$ java Server 3128
$ java Client localhost 3128 movie.Mjpeg
```

Licensing
----
Copyright 2020 Pedro Henrique R M Santos.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
