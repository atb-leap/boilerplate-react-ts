FROM node:10.15.3-alpine

WORKDIR /app
EXPOSE 3000
CMD ["yarn", "start"]

COPY package* ./
RUN yarn install
COPY . .