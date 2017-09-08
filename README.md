# build-concourse
build concourse with docker-compose (See https://concourse.ci/docker-repository.html)

## prepare the environment.

Execute the command as follows:

```
$ bash scripts/install-docker.sh
```

Need to reboot the server then, execute the command as follows.

```
$ bash scripts/install-docker-compose.sh
```

Then, you can use concouse after execute following command.

```
$ export CONCOURSE_EXTERNAL_URL=http://<Your server's ip address>:8080
$ bash run.sh
```
