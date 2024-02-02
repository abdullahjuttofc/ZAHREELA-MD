FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/abdullahjuttofc/ZAHREELA-MD /root/ZAHREELA-MD
WORKDIR /root/ZAHREELA-MD/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
 
