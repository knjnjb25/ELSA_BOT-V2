FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/knjnjb25/ELSA_BOT-V2 /root/knjnjb25
WORKDIR /root/knjnjb25/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
