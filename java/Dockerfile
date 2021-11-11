FROM adoptopenjdk/openjdk11:x86_64-apline-jdk-11.0.11_9

RUN apk --no-cache add msttcorefonts-installer fontconfig && \
    update-ms-fonts && \
    fc-cache -f
