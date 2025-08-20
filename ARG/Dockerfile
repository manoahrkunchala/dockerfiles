ARG version
FROM almalinux:${version:-9}
ENV course="devops" \
    duration="120hr"
ARG trainer="Manohar"
ENV trainer=$trainer
RUN echo " the course name is: ${course}, duration is :${duration} and trainer is : ${trainer}"
CMD [ "sleep","1000" ]

