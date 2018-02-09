FROM node:carbon

# Create app directory
WORKDIR /usr/src/website

RUN git clone https://f792de9a258655ca51896c303f4864a797eee326:x-oauth-basic@github.com/G-Global/WebSite.git .

RUN npm install

CMD [ "npm", "start" ]