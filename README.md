![preview](preview.jpg)

### Install
```
curl -Ss https://raw.githubusercontent.com/b1337xyz/qbfetch/main/qbfetch.py -o ~/.config/qutebrowser/qbfetch.py
```
or
```
wget -q https://raw.githubusercontent.com/b1337xyz/qbfetch/main/qbfetch.py -O ~/.config/qutebrowser/qbfetch.py
```

```
echo "config.source('qbfetch.py')" >> ~/.config/qutebrowser/config.py

# Optional
echo "config.bind('<Ctrl-h>', 'qbfetch')" >> ~/.config/qutebrowser/config.py
```

---
Inspired by [qutefetch](https://github.com/Dou2ble/qutefetch)
