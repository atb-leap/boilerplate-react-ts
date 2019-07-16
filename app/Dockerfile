FROM node:10.15.3-alpine

WORKDIR /app
EXPOSE 3000
CMD ["npm", "start"]

COPY package* ./
RUN npm install
COPY . .