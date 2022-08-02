FROM node:14-alpine AS todofrontend
EXPOSE 3000
WORKDIR /docker/todo-app/front-end
ADD node_modules.tar.gz /docker/todo-app/front-end
COPY . .
CMD ["npm", "start"]

