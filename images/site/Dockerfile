FROM node:carbon

# Create app directory
WORKDIR /usr/src/website

RUN git clone https://b5c266134295a2e66a829a0cabaeba7d51fa09a1:x-oauth-basic@github.com/G-Global/WebSite.git .

RUN npm install

CMD [ "npm", "start" ]