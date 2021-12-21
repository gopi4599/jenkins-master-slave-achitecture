FROM jenkins/jenkins
MAINTAINER gopib450@gmail.com

RUN /usr/local/bin/install-plugins.sh github
RUN /usr/local/bin/install-plugins.sh docker-plugin
RUN /usr/local/bin/install-plugins.sh saferestart

ENV JENKINS_MIRROR http://mirrors.jenkins-ci.org
ENV JAVA_OPTS="-Djenkins.install.runSetupWizard=false"
