# 双向验证演示

## 情景1 验证“非对称密钥对”的“加密”和“解密”

公钥加密 私钥解密

私钥加密 公钥解密 

EncryptAndDecrypt


## 情景2 验证“数字证书”签名

验证私钥签名，公钥检验

VerifySignature


## 情景3 验证“数字证书”是否由“根证书签发”

验证 CA 的数字证书 是由 CA 私钥进行签名的

验证 Intermediate 的数字证书 是由 CA 私钥进行签名的

验证 Server 的数字证书 是由 Intermediate 进行签名的

验证 Server 的数字证书 是由 CA 进行签名的

VerifyCertificate


## 情景4 服务端的单向 SSL 沟通

验证 Server 安装数字证书，通过浏览器访问

验证 Server 安装数字证书，通过 HttpsURLConnection 访问

SingleSSLCommunicate


## 情景5 服务端 和 终端 的双向 SSL 沟通
 




