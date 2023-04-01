FROM kalilinux/kali-rolling

#Requried for console-setup package
COPY files/keyboard /etc/default/keyboard

RUN apt-get update &&  \
    DEBIAN_FRONTEND=noninteractive apt-get install -y kali-linux-headless && \
    rm -rf /var/lib/apt/lists/*
