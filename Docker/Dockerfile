FROM openjdk

#Set Jmeter version and path
ENV JMETER_VERSION=5.3
ENV JMETER_HOME=/usr/src/apache-jmeter${JMETER_VERSION}

#Jmeter folder will be copied to local directory inside the Docker container
ADD apache-jmeter-5.3.tgz /usr/local/

#Create folders to store results
RUN mkdir /load-test
