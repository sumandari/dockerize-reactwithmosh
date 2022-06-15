FROM node:8.11.3

RUN mkdir /app
WORKDIR /app

ENV PATH /app/node_modules/.bin:$PATH

COPY package.json ./
COPY package-lock.json ./
RUN npm install --silent

# add files
COPY index.js ./
COPY seed.js ./

# start app
CMD node seed.js && node index.js
