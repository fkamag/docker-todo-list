FROM mjgargani/puppeteer:trybe1.0 AS todotests
WORKDIR /docker/todo-app/tests
ADD node_modules.tar.gz /docker/todo-app/tests
COPY . .
CMD ["npm", "test"]
