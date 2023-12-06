    FROM node:20.9.0

    COPY package.json /app/
    COPY src /app/
    
    WORKDIR /app

    RUN npm install
 
    CMD [ "node","index.js" ]
     