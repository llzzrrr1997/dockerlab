#构建参数与 ENV 作用相同，都是设置环境变量。不同的是， ARG 设置的构建环境的环境变量在以后容器运行时将不存在。但不要使用 ARG 来保存密码等，因为 docker history 仍然可以看到所有的值。
FROM alpine:3.18
ARG WELCOME_USER=Collabnix
RUN echo "Welcome $WELCOME_USER, to Docker World!" > message.txt
CMD cat message.txt

#在映像构建期间使用 –build-arg 标志传递参数（WELCOME_USER）
# docker image build -t arg:v2 --build-arg WELCOME_USER=Savio .