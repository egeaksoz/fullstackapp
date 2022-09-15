FROM node:16-alpine
 
ADD . /frontend
WORKDIR /frontend
RUN npm install --silent
 
CMD ["npm", "start"]