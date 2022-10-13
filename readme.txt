reference : https://cloud.spring.io/spring-cloud-config/multi/multi__spring_cloud_config_server.html
$ cd $HOME
$ mkdir config-repo
$ cd config-repo
$ git init .
$ echo info.foo: bar > application.properties
$ git add -A .
$ git commit -m "Add application.properties"