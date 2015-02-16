#  Voting

This project is an experiment for voting over websockets.

* Websockets are handled by [websocketd](http://websocketd.com/)
* Vote storage is handled by [redis](http://redis.io/)
* Server is written in [Nim](http://nim-lang.org/)
* Client UI built using [React](http://facebook.github.io/react/)


    nim c -d:release vote.nim
    websocketd --port=8080 ./vote
    open client/index.html

