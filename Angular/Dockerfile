FROM node:14-alpine
WORKDIR /testapp
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build -- --test
EXPOSE 4200
CMD ["npm", "start"]
