FROM nginx:1.23.3-alpine

ADD vaultwarden_michellepellon_com.pem /vaultwarden_michellepellon_com.pem
ADD vaultwarden_michellepellon_com.key /vaultwarden_michellepellon_com.key
ADD default.conf.template /default.conf.template
ADD run_nginx.sh /run_nginx.sh

RUN chmod +x /run_nginx.sh
