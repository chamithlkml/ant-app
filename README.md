# ant-app
Basic package setup for Laravel, Vue, Inertia, Bootstrap with docker deployment. You can quickly start developments without spending hours on setting environment up and running for your project.

### Start docker containers
```
make up
```
This will download docker mysql image and Ubuntu 22.04 image required for setting the PHP app and bind your local machine's port 80 to the App so that you should be able to view the app by login into http://localhost

### Shut down docker containers
```
make down
```
This will shutdown the docker containers

### Delete docker containers, volumes and images
```
make remove
```

### Reload docker containers
```
make reload
```
In case if you have added any composer module or npm module, you need to reload the docker. For that, you can use above command.