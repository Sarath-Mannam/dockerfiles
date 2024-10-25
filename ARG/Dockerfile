ARG version
FROM almalinux:${version:-8}
# ARG variable before FROM will not have access scope after FROM, Which means that it has access scope till FROM instruction
RUN echo "version passed by user is:${version}"
