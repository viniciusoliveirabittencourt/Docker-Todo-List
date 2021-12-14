FROM node:lts-alpine
WORKDIR /docker/todo-app/front-end
EXPOSE 3000
COPY package*.json ./
RUN npm install
ADD node_modules.tar.gz .
COPY . .
CMD ["npm", "start"]
