FROM ubuntu
RUN apt-get update && apt-get install curl -y
RUN curl -I www.google.com
ENTRYPOINT ["curl"]