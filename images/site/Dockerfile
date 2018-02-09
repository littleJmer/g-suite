FROM node:carbon

# Create app directory
WORKDIR /usr/src/website

RUN git clone https://07a37d37f29cb1f95a3941a88a96b27c025abbd4:x-oauth-basic@github.com/G-Global/WebSite.git .

RUN npm install

CMD [ "npm", "start" ]