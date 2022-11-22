FROM nginx
RUN ["mkdir","dist"]
RUN ["touch","/etc/nginx/conf.d/default.conf"]
COPY ./dist /dist
COPY ./default.conf /etc/nginx/conf.d/default.conf