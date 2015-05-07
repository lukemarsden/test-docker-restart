```
docker run --restart=always --name restarter -ti -v /tmp:/file test-docker-restart sh
```

Observe that `docker ps -a` doesn't show the container attempting to be restarted.
