docker image rm $(docker image ls -q)
docker image ls -q

docker build -t dkong1321/deep-dive-phase-1 .
