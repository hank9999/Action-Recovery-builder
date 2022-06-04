# 使用 Github Action 编译 Recovery

---


**如果你的 DT 启用了解密相关，请 Revert [该提交](https://github.com/YuKongA/Action-Recovery-builder/commit/29ddaea3f93c01bb8033a96585acd3a9d8bce03c)以成功编译！**

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
| `DEVICE_URL` | 设备地址 | https://github.com/YuKongA/device_xiaomi_rubens-TWRP.git |
| `DEVICE_BRANCH` | 设备分支 | twrp-12 |
| `DEVICE_PATH` | 设备位置 | device/xiaomi/rubens |
| `DEVICE_NAME` | 设备代号 | rubens |
| `BUILD_TARGET` | 构建目标 | recoveryimage \ bootimage \ vendorbootimage |

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
