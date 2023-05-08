FROM node:14-alpine
EXPOSE 3000
WORKDIR /docker/todo-app/front-end/
ADD /node_modules.tar.gz .
COPY . .
CMD [ "npm", "start" ]