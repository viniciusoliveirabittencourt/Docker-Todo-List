FROM node:lts-alpine
WORKDIR /docker/todo-app/back-end
EXPOSE 3001
COPY package*.json ./
RUN npm install
ADD node_modules.tar.gz .
COPY . .
CMD ["npm", "start"]
