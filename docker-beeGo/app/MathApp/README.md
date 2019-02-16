# Setup


# Run Docker Dev:

Removes itself when instance shut down. Port 8080 map path.... Probably should've done this properly...
```bash
docker run -it --rm --name ma-instance -p 8080:8080 -v /Users/slim/abs-app-dir/docker-beeGo/app/MathApp:/go/src/MathApp -w /go/src/MathApp ma-image
```

Success:
```
______
| ___ \
| |_/ /  ___   ___
| ___ \ / _ \ / _ \
| |_/ /|  __/|  __/
\____/  \___| \___| v1.10.0
2019/02/16 07:02:51 INFO     ▶ 0001 Using 'MathApp' as 'appname'
2019/02/16 07:02:51 INFO     ▶ 0002 Initializing watcher...
MathApp
2019/02/16 07:02:53 SUCCESS  ▶ 0003 Built Successfully!
2019/02/16 07:02:53 INFO     ▶ 0004 Restarting 'MathApp'...
2019/02/16 07:02:53 SUCCESS  ▶ 0005 './MathApp' is running...
2019/02/16 07:02:53.570 [I]  http server Running on http://:8080
```
Check BeeGo page at URL: `http://localhost:8080/sum/4/5`
