
Keycrhon Function key Solution
```
echo 2 | sudo tee /sys/module/hid_apple/parameters/fnmode
```
```
/etc/modprobe.d/hid_apple.conf

options hid_apple fnmode=2
```
