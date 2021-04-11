Auf Anfrage bekommt der Client eine Liste aller Channels vom Server übergeben.

Ein Channel hat eine ID(evtl. Portnummer) und einen Namen.

Client
from: *client*
to: *server*
msg: ""
method: getChannels
created: *date*

Server
from: *server*
to: *client*
msg: *channelArray*
method: getChanneles
created: *date*

