## i3 config
Config location may vary by install. See package instructions

Typically:

```console
mv config ~/.config/i3/config
```

## i3blocks
Requires i3blocks: https://github.com/vivien/i3blocks

```
# as of 2020-11-26
git clone https://github.com/vivien/i3blocks
cd i3blocks
./autogen.sh
./configure
make
make install
```

(i3blocks scripts placed in /usr/share/i3blocks)


```console
cp i3blocks /usr/share/i3blocks
mv i3blocks.conf ~/.i3blocks.conf
```

