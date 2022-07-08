FROM node:14-alpine
# WORKDIR GK
WORKDIR /app
COPY ./node_modules.tar.gz .
COPY . .
# NPM INSTALL
RUN npm install
CMD [ "npm", "start" ]
EXPOSE 3001
