# jenkins-flake8

This is a docker image based on `jenkins/jnlp-slave:alpine` and designed to be used with the Jenkins [Docker Plugin](https://wiki.jenkins.io/display/JENKINS/Docker+Plugin)

It contains python3 and flake8 with a lot of plugins. Drop your own `.flake8`
in your source to override default values.
