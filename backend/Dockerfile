FROM node:latest

WORKDIR /backend/

# Copy package.json and package-lock.json (if available)
COPY package.json /backend/
COPY package-lock.json /backend/ 

# Install dependencies
RUN npm install

# Copy all files
COPY . /backend/

EXPOSE 4000

CMD ["npm", "start"]
