FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/maxindude005/maxindude /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/maxindude005/Nandhuttynew
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
