# jenkins-flake8

This is a docker image based on `jenkins/jnlp-slave:alpine` and designed to be used with the Jenkins [Docker Plugin](https://wiki.jenkins.io/display/JENKINS/Docker+Plugin)

It contains python3 and flake8 with a lot of plugins. Drop your own `.flake8`
in your source to override default values.

## Manual usage

If you want to use the same image on your local codebase to adjust the flake8 settings you can do this:

    $ docker run -it --rm -v /path/to/mycode:/project mecodia/jenkins-flake8 bash
    $ flake8 /project
