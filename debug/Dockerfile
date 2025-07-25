# Creating a Debug image for running the catalogue component. while checking the health 
# check of catlaogue component and mongodb is connect to catalogue or not.
# This image is useful

FROM almalinux:9
RUN dnf install telnet net-tools iputils -y
RUN useradd roboshop
USER roboshop
CMD ["sleep","100000"]

