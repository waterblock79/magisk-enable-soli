# Magisk Enable Soli

Motion Sense was banned in some area and this module will enable it again.

该模块用于在 Motion Sense 被禁用的地区重新启用 Motion Sense 功能。

它实际上是在开机时执行了：

```
setprop pixel.oslo.allowed_override 1
setprop persist.pixel.oslo.allowed_override 1
```

## Thanks / 感谢

  - [@topjohnwu](https://github.com/topjohnwu)
  - [@Pinkdoge](https://github.com/pinkdoge)（[Magisk Moudle Template](https://github.com/Pinkdoge/magisk-module-template)）

