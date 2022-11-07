# A dockerfile must always start by importing the base image.
# We use the keyword 'FROM' to do that.
# In our example, we want import the python image.
# So we write 'python' for the image name and 'latest' for the version.
FROM python:3.8-alpine

RUN apk add --update npm

# We need to define the command to launch when we are going to run the image.
# We use the keyword 'CMD' to do that.
ENTRYPOINT ["sh"]



