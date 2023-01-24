FROM node:18-alpine3.17
WORKDIR /app
COPY package.json /app
RUN npm install
# Se vamos instalar os pacotes dentro do container, vamos ignorar node_modules durante a cópia
COPY . .
EXPOSE 8080
CMD ["npm", "start"]