FROM ubuntu:20.04 

RUN apt update && apt install -y curl

CMD while true;do echo "Input website:";read website; echo "Searching..";sleep 1; curl http://$website; done 
