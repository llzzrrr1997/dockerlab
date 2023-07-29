#Dockerfile 中的 ENV 指令在启动时为容器设置环境变量。启动容器时可以通过传递 --env <key>=<value> 来覆盖默认值。
FROM alpine:3.18
ENV WELCOME_MESSAGE="Welcome to Docker World"

CMD ["sh", "-c", "echo $WELCOME_MESSAGE"]