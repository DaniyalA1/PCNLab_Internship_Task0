FROM node:latest

WORKDIR /frontend/

# Copy package.json and package-lock.json (if available)
COPY package.json /frontend/
COPY package-lock.json /frontend/ 

# Install dependencies
RUN npm install

# Copy all files
COPY . /frontend/

EXPOSE 3000

CMD ["npm", "start"]
