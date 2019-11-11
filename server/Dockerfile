FROM node:apline
WORKDIR "/doodee24/app"
COPY ./package.json ./
RUN nmp install
COPY . .
CMD ["npm", "run", "start"]