FROM node

EXPOSE 3001

WORKDIR /usuarios

COPY controllers /usuarios/controllers
COPY models /usuarios/models
COPY index.js /usuarios

RUN npm init --yes
RUN npm install express morgan mysql mysql2 axios 

CMD node index.js
