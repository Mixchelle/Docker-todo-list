
FROM mjgargani/puppeteer:trybe1.0
WORKDIR /docker/todo-app/test/
ADD /node_modules.tar.gz ./
COPY ./ ./
CMD [ "npm", "start" ]