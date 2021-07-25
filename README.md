# This is a tool extracted from Android 11r39 code for generating sepolicy
## Usage:
```
adb pull /sys/fs/selinux/policy
adb logcat -b all -d | python3 ./audit2allow -p ./policy
``` 
