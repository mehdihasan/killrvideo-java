# KillrVideo Java - Version 3.0.1 #

```bash
cd scripts
export KILLRVIDEO_BACKEND=`ipconfig getifaddr en0`
docker-compose -p killrvideo-java -f docker-compose-backend-external.yaml up -d
```

Now, make sure that the DSE is running.

Then, start the killrvideo-service module.


