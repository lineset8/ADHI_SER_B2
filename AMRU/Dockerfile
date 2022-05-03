FROM fusuf/whatsasena:latest

RUN git clone https://github.com/lineset8/ADHI_SER_B2 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines

CMD ["node", "bot.js"]
