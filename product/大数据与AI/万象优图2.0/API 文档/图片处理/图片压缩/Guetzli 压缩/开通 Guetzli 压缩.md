## 功能描述
对 Bucket 开通 Guetzli 压缩功能。

## 请求

#### 请求示例

```
PUT /?guetzli HTTP/1.1
Host: <BucketName-APPID>.pic.<Region>.myqcloud.com 
Date: GMT Date
Authorization: Auth String
```

>?
> - Authorization: Auth String（详情请参见 [请求签名](https://cloud.tencent.com/document/product/436/7778) 文档）。
> - 通过子账号使用时，需要授予相关的权限，详情请参见 [授权粒度详情](https://cloud.tencent.com/document/product/460/41741) 文档。
> - Guetzli 压缩目前暂不支持通过 COS 域名使用，请参考示例使用 pic 域名。
>

#### 请求行

```
PUT /?guetzli HTTP/1.1
```
该 API 接口接受 PUT 请求。

#### 请求头

#### 公共头部

该请求操作的实现使用公共请求头，了解公共请求头详情，请参阅 [公共请求头部](https://cloud.tencent.com/document/product/436/7728) 章节。

#### 非公共头部

该请求操作无特殊的请求头部信息。

#### 请求体
该请求的请求体为空。

## 响应

#### 响应头

#### 公共响应头

该响应使用公共响应头，了解公共响应头详情，请参阅 [公共响应头部](https://cloud.tencent.com/document/product/436/7729) 章节。

#### 特有响应头

该响应无特殊的响应头。

#### 响应体
该响应体返回为空。
  
