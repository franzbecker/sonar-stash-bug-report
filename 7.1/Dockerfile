FROM sonarqube:7.1

USER sonarqube
RUN cd /opt/sonarqube/extensions/plugins/ && \
    wget https://sonarsource.bintray.com/Distribution/sonar-java-plugin/sonar-java-plugin-5.7.0.15470.jar && \
    wget https://sonarsource.bintray.com/Distribution/sonar-scm-git-plugin/sonar-scm-git-plugin-1.4.1.1128.jar && \
    wget https://github.com/AmadeusITGroup/sonar-stash/releases/download/1.4.0/sonar-stash-plugin-1.4.0.jar

USER root
