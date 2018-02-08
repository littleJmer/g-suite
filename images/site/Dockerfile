FROM node:carbon

# Create app directory
WORKDIR /usr/src/website

RUN git clone https://a5cdb086662de5af846ff28300c11b3ccd4dad34:x-oauth-basic@github.com/G-Global/WebSite.git .

RUN npm install

CMD [ "npm", "start" ]