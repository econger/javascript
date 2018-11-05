FROM node:8

# Create an app directory
WORKDIR /usr/src/app

# Install app dependencies.
COPY package*.json ./

# Install dependencies
RUN npm install

# Bundle app source
COPY . .

# Expose the app port
EXPOSE 8080

# Finally, run the code
CMD [ "npm", "start" ]
