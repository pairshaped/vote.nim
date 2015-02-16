#  Voting w/ Nim + Redis + websocketd

    nim c -d:release vote.nim
    websocketd --port=8080 ./vote

