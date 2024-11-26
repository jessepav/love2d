## Configure

This was my configure command:

```sh
CFLAGS="-I/opt/SDL2/include" LDFLAGS="-L/opt/SDL2/lib" \
    ./configure --prefix=/opt/love2d --with-lua=luajit --with-luaversion=5.1
```
