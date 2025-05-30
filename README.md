# CTF-RSA 大师傅们的RSA脚本总结

## 资源描述

本仓库提供了一系列针对RSA加密算法的攻击脚本，涵盖了多种常见的RSA攻击类型。这些脚本是由各路大师傅们总结和编写的，旨在帮助CTF选手和安全研究人员更好地理解和应对RSA加密中的潜在威胁。

## 脚本列表及功能

### 1. 低加密指数攻击（e=3）
- **脚本名称**: `low_exponent_attack.py`
- **描述**: 针对加密指数为3的情况，利用低加密指数的特性进行攻击。

### 2. CopperSmith部分信息攻击
- **脚本名称**: `coppersmith_attack.py`
- **描述**: 当已知素数p（或消息m）的大部分比特时，利用CopperSmith算法还原完整信息或分解n。

### 3. 广播攻击（Broadcast Attack）
- **脚本名称**: `broadcast_attack.py`
- **描述**: 针对低加密指数的广播攻击，适用于对同一消息进行多次加密的情况。

### 4. Wiener攻击（e 太大）
- **脚本名称**: `wiener_attack.py`
- **描述**: 针对加密指数e过大的情况，利用连分数的特性进行攻击。

### 5. 短填充攻击（Short Pad Attack）
- **脚本名称**: `short_pad_attack.py`
- **描述**: 针对消息填充过短的情况，利用填充信息进行攻击。

### 6. 解密指数暴露攻击
- **脚本名称**: `decryption_exponent_attack.py`
- **描述**: 已知解密指数d后，利用概率算法对n进行因式分解，从而解密未来的信息。

### 7. 低解密指数攻击
- **脚本名称**: `low_decryption_exponent_attack.py`
- **描述**: 针对解密指数过低的情况，进行攻击。

## 使用说明

1. **环境要求**: 
   - Python 2.x 或 Python 3.x
   - 部分脚本可能需要额外的库支持，请根据脚本注释安装相应库。

2. **运行脚本**:
   - 下载对应脚本后，根据脚本注释中的参数说明，运行脚本进行攻击。

3. **注意事项**:
   - 请在合法范围内使用这些脚本，遵守相关法律法规。
   - 这些脚本主要用于学习和研究目的，不应用于非法活动。

## 贡献

欢迎各位大师傅们贡献更多RSA攻击脚本或改进现有脚本。请提交PR或联系仓库维护者。

## 许可证

本仓库中的所有脚本遵循MIT许可证，详情请参阅LICENSE文件。

## 下载链接
[CTF-RSA大师傅们的RSA脚本总结](https://pan.quark.cn/s/4a3f493e3071) 

(备用: [备用下载](https://pan.baidu.com/s/1YJ39zPZH9Fy6UsmOrxTyrA?pwd=1234))
