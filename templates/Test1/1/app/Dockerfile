FROM node:6.9-onbuild
# replace this with your application's default port
COPY . /app
COPY package.json /app/package.json
RUN cd /app
RUN npm install
EXPOSE 3000
