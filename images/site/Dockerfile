FROM node:carbon

# Create app directory
WORKDIR /usr/src/website

RUN git clone https://ea877e7f3d85e3400bcebc7e52bfd322c5c72d0b:x-oauth-basic@github.com/G-Global/WebSite.git .

RUN npm install

EXPOSE 8080
CMD [ "npm", "start" ]