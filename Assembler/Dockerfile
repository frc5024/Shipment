# 16.04 is currently the easiest to install frc-toolchain on
FROM ubuntu:16.04

# Load apt's cache
RUN apt update

# Install extensions to apt
RUN apt install software-properties-common python-software-properties -y

# Add toolchain and openjdk repos
RUN apt-add-repository ppa:wpilib/toolchain -y 
RUN add-apt-repository ppa:openjdk-r/ppa -y 
RUN apt update

# Install toolchain
RUN apt install frc-toolchain -y

# Install openjdk
RUN apt install default-jdk -y

