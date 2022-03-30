FROM ubuntu:16.04
LABEL author="Kuanysh Sultan"

WORKDIR "/kuanysh"
COPY sc.sh .
RUN apt-get update && apt-get install -y curl && chmod u+x sc.sh
CMD ["./kuanysh/sc.sh helsinki.fi"]