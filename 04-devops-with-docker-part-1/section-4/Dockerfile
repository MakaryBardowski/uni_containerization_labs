FROM ubuntu:22.04

RUN apt update && apt install -y curl

COPY script.sh /usr/local/bin/script.sh

RUN chmod +x /usr/local/bin/script.sh

ENTRYPOINT ["sh","/usr/local/bin/script.sh"]
