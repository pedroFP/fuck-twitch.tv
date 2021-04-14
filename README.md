# my-twitch.tv
Build your own live-streaming app!

![image](https://user-images.githubusercontent.com/22729642/112779209-94828d80-901c-11eb-9618-47931ff7a74a.png)

``` js
// rtmp/index.html
var videoSrc = "http://localhost:8080/hls/<CHANGE_TO_STREAM_PATH>.m3u8";
```

In this case `CHANGE_TO_STREAM_PATH` is `test` but you can change that to whatever you want

<hr>

### This branch separated the stream `auth`


```
$ docker-compose build
```

```
$ docker-compose up
```

`locahost:8080`

### Enjoy! 😉

Based on this [video](https://www.youtube.com/watch?v=yKdPSXkaV5c)
