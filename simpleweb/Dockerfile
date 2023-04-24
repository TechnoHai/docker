#specify a base image
FROM node:14-alpine

#Making a work direcctory so the files will be copy to it and will be exetcuet fro there
WORKDIR /usr/app

#Copy file from the current directort to the container current directory
COPY ./ ./

#install some dependencies 
RUN npm install 

#Default command
CMD ["npm","start"]
