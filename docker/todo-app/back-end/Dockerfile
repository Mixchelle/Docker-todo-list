FROM node:14-alpine
EXPOSE 3001
WORKDIR /docker/todo-app/back-end/
ADD /node_modules.tar.gz ./
COPY ./ ./
CMD [ "npm", "start" ]
