FROM node:14-alpine AS todobackend
EXPOSE 3001
WORKDIR /docker/todo-app/back-end
ADD node_modules.tar.gz /docker/todo-app/back-end
COPY . .
CMD ["npm", "start"]
