# corenlp-docker
Dockerfile for Stanford CoreNLP Server
---------

This Dockerfile builds the [Stanford CoreNLP
Server](http://stanfordnlp.github.io/CoreNLP/corenlp-server.html) and exposes
the endpoint on port 9000. Requests are made as covered in the documentation.

`updated to latest version: stanford-corenlp-full-2018-10-05`

## Usage

```
docker run -p 9000:9000 --name coreNLP --rm -i -t isslab/corenlp:2018-10-05
```