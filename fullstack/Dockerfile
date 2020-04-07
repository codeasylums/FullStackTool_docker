FROM codercom/code-server
USER root

# ENTRYPOINT /bin/bash
# ENV DEBIAN_FRONTEND noninteractive

ENV PASSWORD=summercodeasylums
RUN   apt-get update && \
    #   apt-get install -y --no-install-recommends apt-utils \
      apt-get -y install  curl wget && \
      curl -sL https://deb.nodesource.com/setup_12.x | sudo  -E bash - && \
      apt-get -y install dirmngr apt-transport-https lsb-release ca-certificates && \
      apt-get -y install nodejs && \
      wget -qO - https://www.mongodb.org/static/pgp/server-4.2.asc | sudo apt-key add - && \
      echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu bionic/mongodb-org/4.2 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.2.list && \
      apt-get update && \ 
      apt-get -y install mongodb-org && \
      rm -rf /var/lib/apt/lists/*

# EXPOSE 3000 3001 3002 3003 3004 3005 80 443 22 27017 8080

