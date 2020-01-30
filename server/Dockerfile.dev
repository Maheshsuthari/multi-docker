FROM node:alpine
WORKDIR '/app'
COPY ./package.json ./
RUN npm install --silent
RUN npm install react-scripts@3.0.1 -g --silent
COPY . .
CMD ["npm", "run", "start"]