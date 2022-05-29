# 使用 Github Action 编译 Recovery

---

## 更新说明
```
2022.05.30: 
- 现在可以用来编译最新的 twrp-12.1 分支了
```

-----

## 参数说明

| 名称 | 描述 | 示例 |
| ------------ | -------------------- | ------------ |
| `LIBRARY_NAME` | 源码类型 | twrp |
| `LIBRARY_URL` | 源码地址 | https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.git |
| `LIBRARY_BRANCH` | 源码分支 | twrp-12.1 |
| `DEVICE_URL` | 设备树地址 | https://github.com/YuKongA/recovery_device_xiaomi_rubens.git |
| `DEVICE_BRANCH` | 设备树分支 | twrp-12 |
| `DEVICE_PATH` | 设备树位置 | device/xiaomi/rubens |
| `DEVICE_NAME` | 机型名称 | rubens |

-----

## 如何使用
```
例如你的用户名为: Fun-114514
```
#### 1、点击本仓库右上角的 'Fork'
![](https://i.bmp.ovh/imgs/2021/10/6b6ed9f29e732372.png)
#### 2、等待自动跳转后，你会看到你自己的用户名
![](https://i.bmp.ovh/imgs/2021/10/66cfe324c0ebb69b.png)
#### 3、点击 'Actions - Make Recovery'
![](https://i.bmp.ovh/imgs/2021/10/23896d1b66292047.png)
#### 4、点击 'Run workflow' 并按照上文 '参数说明' 填写
![](https://i.bmp.ovh/imgs/2021/10/9cb7871267cf2f53.png)
#### 5、填写完成后点击 'Run workflow' 开始运行

-----

## 编译结果
可以在 [actions](../../actions) 下载
