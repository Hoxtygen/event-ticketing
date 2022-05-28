FROM node:16-alpine

WORKDIR /app
COPY package.json .
# --only=prod added to prevent the installation of devDependencies
RUN npm install --only=prod
COPY . .


CMD ["npm", "start"]