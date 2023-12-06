FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/Itxxwasi/SIGMA-MD-wasi /root/https:/Itxxwasi/SIGMA-MD-wasi
WORKDIR /root/Itxxwasi/SIGMA-MD-wasi/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
 
 
