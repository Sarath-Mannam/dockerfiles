ARG version
FROM almalinux:${version:-8}
# ARG variable before FROM will not have access scope after FROM, Which means that it has access scope till FROM instruction
ARG COURSE
ARG TRAINER
RUN echo "Course is: ${COURSE}, trainer is: ${TRAINER}""