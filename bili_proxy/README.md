# 解除B站区域限制代理服务器PHP脚本

### 1. PHP空间

需要绑定域名和证书,如果空间提供商有就可以用他的,也有免费的.将BPplayurl.php重命名index.php上传到空间的根目录下即可.由于每个空间提供商操作都不同,详细步骤请自行摸索

### 2. 阿里云函数计算

[阿里云函数计算](https://www.aliyun.com/product/fc)按次计费，~~有免费额度~~ 公网流量已经没有免费额度,注意费用。参考@realLyans写的[简易教程](https://github.com/ipcjs/bilibili-helper/issues/710#issuecomment-748976481)

~~阿里云函数计算版本添加多接口支持后和油猴脚本(8.2.3)不兼容，需要在链接后面添加`playurl`暂时规避~~<br>
阿里云函数计算的公网链接做了修改,已可直接使用<br>
旧版`https://1111111111111111.cn-hongkong.fc.aliyuncs.com/2016-08-15/proxy/bili.LATEST/bili/`<br>
新版`https://biliproxy-bili-adadzfzc.cn-hongkong.fcapp.run`

## 自建代理服务
香港`https://repost.98e.org` 



## 手动授权流程
[跳转链接](https://github.com/zzc10086/grocery_store/blob/master/bili_proxy/auth.md)
