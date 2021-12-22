FROM fusuf/whatsasena:latest

RUN git clone https://github.com/mhmdmukrim/DEVIL_v2 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/farhan-dqz/media
RUN git clone https://github.com/ravindu01manoj/Sew-Queen

CMD ["node", "bot.js"]
