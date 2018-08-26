FROM openresty/openresty:1.13.6.1-alpine-fat

RUN /usr/local/openresty/luajit/bin/luarocks install lua-resty-http && \
    /usr/local/openresty/luajit/bin/luarocks install lua-resty-string && \
    /usr/local/openresty/luajit/bin/luarocks install lua-resty-nettle
