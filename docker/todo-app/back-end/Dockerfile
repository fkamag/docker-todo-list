FROM node:14-alpine AS todobackend
EXPOSE 8080
WORKDIR /todo-app/back-end
ADD node_modules.tar.gz /todo-app/back-end
COPY . .
CMD ["npm", "start"]
