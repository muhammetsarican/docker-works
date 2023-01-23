FROM ubuntu:18.04
RUN apt-get update
RUN apt install curl -y
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt-get install nodejs -y
# WORKDIR /opt/node-app/
# COPY . .
COPY index.js /opt/node-app/
ENV channel=www.muhammetsarican.com
# WORKDIR /opt/node-app/
# CMD ["node", "index.js"]
CMD ["node", "/opt/node-app/index.js"]