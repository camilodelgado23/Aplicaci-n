FROM node 

EXPOSE 3002

WORKDIR /productos

COPY controllers /productos/controllers 
COPY models /productos/models
COPY index.js /productos 

RUN npm init --yes
RUN npm install express morgan mysql mysql2 axios 

CMD node index.js 
