# anykernel

Automatic script for installing the Android kernel in recovery

```bash
git clone --depth=1 https://github.com/jzinferno/anykernel.git
cd anykernel
cp -r jd2019/META-INF .
cp /path/to/Image.gz-dtb .
cp /path/to/dtbo.img .
sed -i 's/KERNELVERSION/4.9.325/g' META-INF/com/google/android/update-binary
zip -r9 kernel.zip META-INF bin Image.gz-dtb dtbo.img
```
