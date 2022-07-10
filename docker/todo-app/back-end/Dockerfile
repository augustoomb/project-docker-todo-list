# pegando a imagem base do hub
FROM node:14-alpine

# apontando onde será a pasta base na imagem (vi na doc do projeto)
WORKDIR /todo-app/back-end

# copiando tudo do pc(pasta onde está este dockerfile)para a raiz(WORKDIR)
ADD . .

# comando básico para instalar dependências.
# Já estou copiando e extraindo a pasta node_modules
# Não ficou claro se preciso desse passo. Mas não atrapalhará.
RUN npm install

# expondo a porta solicitada no readme
EXPOSE 3001

CMD [ "npm", "start" ]