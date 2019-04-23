# spscify bsae image
FROM node:alpine
WORKDIR /usr/app
#install some depencies list
#copy command here will reduce build time as npm install is only run if package.json file is run
COPY ./package.json ./
RUN npm install
COPY ./ ./

#default command
CMD ["npm","start"]