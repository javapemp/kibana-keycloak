FROM nginx:1-alpine

RUN rm /etc/nginx/conf.d/default.conf
COPY ./kibana.conf /etc/nginx/conf.d/kibana.conf

#RUN ln -s /etc/nginx/sites-available/dashboard.conf /etc/nginx/sites-enabled/dashboard.conf

