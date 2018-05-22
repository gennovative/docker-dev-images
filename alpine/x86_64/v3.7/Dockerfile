FROM alpine:3.7

RUN apk add --update --no-cache curl wget vim nano && \
    echo -e "syntax on \ncolorscheme delek \nset nu" >  ~/.vimrc && \
    rm -rf /var/lib/apk/lists/* && \
	rm /var/cache/apk/*

CMD ["/bin/sh"]