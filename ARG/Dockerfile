ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG ${COURSE:-Docker}
ARG ${TRAINER:-charan} 
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}"
CMD ["cat", "/etc/*release"]