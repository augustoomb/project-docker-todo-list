FROM node:14-alpine
WORKDIR /docker/todo-app/back-end
EXPOSE 3001
# COPY node_modules.tar.gz ./
COPY ./ ./

RUN npm install
ENTRYPOINT [ "npm", "start" ]