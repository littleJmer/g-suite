FROM node:carbon

# Create app directory
WORKDIR /usr/src/website

RUN git clone https://7aa58f19575ffa0b3f5cfbfd91575cb93ced9f40:x-oauth-basic@github.com/G-Global/WebSite.git .

RUN npm install

CMD [ "npm", "start" ]