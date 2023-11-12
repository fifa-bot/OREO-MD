FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Joker-Ofc/OREO-MD /root/Joker-Ofc
WORKDIR /root/Joker-Ofc/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
