# installation

move exec files under

```
/usr/local/bin/
```

result will be

```
/usr/local/bin/win_path
```

## exec file overview

### winpath

```
winpath smb://192.168.x.x/foo/bar/baz/qux

¥¥192.168.x.x¥foo¥bar¥baz¥qux
```

* remove ```smb:```
* replace ```/``` to ```¥```
* argument format should be ```/smb:\/\/.+/```
