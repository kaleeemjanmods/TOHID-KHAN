FROM quay.io/gurusensei/gurubhay:latest

RUN git clone https://github.com/Tohidkhan6332/TOHID-KHAN /root/global

WORKDIR /root/global/

RUN npm install --platform=linuxmusl

EXPOSE 5000

CMD ["npm", "start"]
