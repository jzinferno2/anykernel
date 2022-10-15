# anykernel

Automatic script for installing the Android kernel in recovery

```bash
git clone https://github.com/jzinferno/anykernel.git
cd anykernel
cp -r jd2019/META-INF .
cp /path/to/Image.gz-dtb .
cp /path/to/dtbo.img .
zip -r9 kernel.zip META-INF bin Image.gz-dtb dtbo.img
```
