FROM node:alpine

WORKDIR /home/ec2-user/webapp

COPY . .

RUN npm install

CMD ["npm", "start"]

# FROM node:alpine

# WORKDIR /webapp

# COPY package.json .

# RUN npm install

# COPY . .

# EXPOSE 80

# CMD ["npm", "start"]


# FROM nginx:latest

# COPY . /usr/share/nginx/html

# WORKDIR /usr/share/nginx/html

# EXPOSE 80

# CMD ["nginx", "-g", "daemon off;"]

# ---------------------------------------------------

