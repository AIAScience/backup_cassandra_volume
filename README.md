# BACKUP Cassandra Docker Volume

[Backup/Restore your containers with data volumes](https://docs.docker.com/engine/tutorials/dockervolumes/)

go to the local directory on the host attached to the Docker volume, then add and push all new files, deletion and modifications:

```shell
cd /home/patechoc/docker/cassandra_volume
git add --all
git commit -am "backup"
git push
```


