FROM 026090548352.dkr.ecr.us-east-1.amazonaws.com/node-base:14
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
CMD [ "npm", "start" ]
