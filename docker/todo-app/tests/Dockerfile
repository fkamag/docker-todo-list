FROM mjgargani/puppeteer:trybe1.0 AS todotests
WORKDIR /todo-app/tests
ADD node_modules.tar.gz /todo-app/tests
COPY . .
CMD ["npm", "test"]
