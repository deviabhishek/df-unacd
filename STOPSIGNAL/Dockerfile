FROM node:14-alpine

# Set the working directory
WORKDIR /app

# Copy the application files
COPY package.json .
COPY index.js .

# Install the dependencies
RUN npm install

# Set the STOPSIGNAL to SIGINT
STOPSIGNAL SIGINT

# Start the application
CMD ["npm", "start"]