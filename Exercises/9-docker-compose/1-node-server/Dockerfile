FROM node:14-slim
WORKDIR /opt/node-server
COPY app/ .
# COPY package* .
# npm install komutu package.json dosyasındaki bilgilere göre node modüllerini yükler.
RUN npm install 
CMD ["node", "app.js"]