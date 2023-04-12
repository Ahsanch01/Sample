FROM node:14-alpine
WORKDIR /testapp
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build
EXPOSE 4100
CMD ["npm", "start"]
