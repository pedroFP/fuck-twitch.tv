# fuck-twitch.tv
Build your own live-streaming app!

![image](https://user-images.githubusercontent.com/22729642/112779209-94828d80-901c-11eb-9618-47931ff7a74a.png)

``` js
// rtmp/index.html
var videoSrc = "http://localhost:8080/hls/<CHANGE_TO_STREAM_PATH>.m3u8";
```

In this case `CHANGE_TO_STREAM_PATH` is `test` but you can change that to whatever you want

<hr>

```JS
// auth/server.js
const streamkey = req.body.key; // => change the key param to any name you'd like but remember to change in the STREAM KEY
if (streamkey === "<PUT A PASSWORD>") { // => set your password to anything you prefer
  res.status(200).send();
  return;
}
```


```
$ docker-compose build
```

```
$ docker-compose up
```

`locahost:8080`

### Enjoy! 😉
