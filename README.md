# 多功能测速脚本

兼容 [speedtest-cli](https://www.speedtest.net/zh-Hans/apps/cli)、[bim-core](https://github.com/veoco/bim-core)、[speedtest-go](https://github.com/showwin/speedtest-go)、[librespeed-cli](https://github.com/librespeed/speedtest-cli)、[iperf3](https://github.com/esnet/iperf)。

脚本自带丰富的测试项目任君挑选，使用者还能自定义想要的测试项目。

目录：👉 [效果展示](https://github.com/i-abc/Speedtest#效果展示)、[使用方法](https://github.com/i-abc/Speedtest#使用方法)、[基本功能](https://github.com/i-abc/Speedtest#基本功能)、[进阶功能](https://github.com/i-abc/Speedtest#进阶功能)

# 效果展示

<details>

<summary>大陆三网+教育网 IPv4 多线程测速 (点击展开或收起)</summary>
 
✈️ 测试服务器：Azure 东京
 
```
------------------------ 多功能 自更新 测速脚本 ------------------------
 Version               : v2023-09-07
 Usage                 : bash <(curl -sL bash.icu/speedtest)
 GitHub                : https://github.com/i-abc/speedtest
------------------------------------------------------------------------
大陆三网+教育网 IPv4 多线程测速，v2023-09-07
------------------------------------------------------------------------
测速节点            下载/Mbps      上传/Mbps      延迟/ms      抖动/ms
最近的测速点        8201.26 Mbps   883.80 Mbps    1.97 ms      0.09 ms      
电信 天津           3616.50 Mbps   961.05 Mbps    68.72 ms     0.22 ms      
电信 甘肃兰州       13.85 Mbps     759.77 Mbps    63.59 ms     2.06 ms      
电信 四川成都       11.87 Mbps     812.11 Mbps    163.53 ms    10.54 ms     
电信 安徽合肥 5G    3807.94 Mbps   961.02 Mbps    38.43 ms     0.46 ms      
电信 江苏镇江 5G    4863.40 Mbps   960.81 Mbps    36.36 ms     0.60 ms      
电信 湖南长沙 5G    2807.66 Mbps   952.72 Mbps    67.41 ms     0.92 ms      
电信 江苏连云港 5G  4310.71 Mbps   44.88 Mbps     34.83 ms     0.23 ms      
移动 北京           2632.46 Mbps   955.66 Mbps    122.76 ms    0.17 ms      
移动 甘肃兰州       6.41 Mbps      932.02 Mbps    136.94 ms    8.23 ms      
移动 广东深圳       11.13 Mbps     653.17 Mbps    187.76 ms    154.31 ms    
移动 浙江杭州 5G    2894.64 Mbps   705.73 Mbps    85.02 ms     0.12 ms      
移动 陕西西安 5G    2685.48 Mbps   957.27 Mbps    133.28 ms    0.30 ms      
联通 江苏无锡       3876.50 Mbps   960.85 Mbps    36.55 ms     0.19 ms      
联通 四川成都       25.62 Mbps     355.90 Mbps    62.15 ms     0.30 ms      
联通 福建福州       5501.38 Mbps     失败         53.53 ms     0.19 ms      
联通 辽宁沈阳       2323.80 Mbps   581.46 Mbps    66.04 ms     0.80 ms      
联通 海南三亚       4729.78 Mbps   923.30 Mbps    76.86 ms     0.05 ms      
联通 湖南长沙 5G    141.74 Mbps    960.81 Mbps    76.18 ms     1.33 ms      
联通 河南郑州 5G    39.73 Mbps     960.70 Mbps    51.34 ms     0.29 ms      
广电 重庆           1.88 Mbps      23.92 Mbps     87.10 ms     0.45 ms      
教育网 江苏苏州     1.07 Mbps      19.53 Mbps     147.53 ms    209.28 ms    
教育网 北京         220.15 Mbps    366.71 Mbps    85.82 ms     0.02 ms      
教育网 上海         241.95 Mbps    262.00 Mbps    197.73 ms    0.79 ms      
教育网 江苏南京     619.21 Mbps    502.79 Mbps    110.64 ms    0.39 ms      
教育网 安徽合肥       失败         635.71 Mbps    106.36 ms    1.16 ms      
------------------------------------------------------------------------
当前时间：2023-09-08 09:30:48 CST
北京时间: 2023-09-08 09:30:48+08:00
------------------------------------------------------------------------
```

</details>

<details>

<summary>大陆三网+教育网 IPv4 单线程测速</summary>
 
✈️ 测试服务器：Azure 东京

```
------------------------ 多功能 自更新 测速脚本 ------------------------
 Version               : v2023-09-07
 Usage                 : bash <(curl -sL bash.icu/speedtest)
 GitHub                : https://github.com/i-abc/speedtest
------------------------------------------------------------------------
大陆三网+教育网 IPv4 单线程测速，v2023-09-07
------------------------------------------------------------------------
测速节点            下载/Mbps      上传/Mbps      延迟/ms      抖动/ms
电信 天津           386.20 Mbps    443.30 Mbps    51.80 ms     4.30 ms      
电信 甘肃兰州       2.40 Mbps      239.10 Mbps    66.40 ms     41.00 ms     
电信 四川成都       0.30 Mbps      6.90 Mbps      125.70 ms    252.40 ms    
电信 湖南长沙 5G    304.00 Mbps    307.80 Mbps    58.00 ms     7.20 ms      
电信 安徽合肥 5G    334.40 Mbps    628.40 Mbps    39.50 ms     0.50 ms      
电信 浙江宁波 5G    235.60 Mbps    581.30 Mbps    37.70 ms     7.50 ms      
电信 江苏镇江 5G    632.40 Mbps    662.10 Mbps    36.60 ms     7.50 ms      
电信 江苏连云港 5G  520.50 Mbps    0.80 Mbps      35.00 ms     1.70 ms      
移动 北京           609.30 Mbps    244.90 Mbps    120.00 ms    2.80 ms      
移动 甘肃兰州         失败         443.50 Mbps    123.50 ms    31.20 ms     
移动 广东深圳       0.50 Mbps      184.90 Mbps    93.20 ms     2.90 ms      
移动 浙江杭州 5G    243.60 Mbps    183.40 Mbps    83.20 ms     2.00 ms      
移动 陕西西安 5G    706.60 Mbps    99.40 Mbps     106.00 ms    8.10 ms      
联通 江苏无锡         失败           失败         35.60 ms     23.20 ms     
联通 四川成都       8.10 Mbps      5.70 Mbps      62.70 ms     1.90 ms      
联通 福建福州       347.80 Mbps    284.70 Mbps    56.20 ms     12.50 ms     
联通 辽宁沈阳       162.50 Mbps    211.50 Mbps    65.70 ms     10.30 ms     
联通 海南三亚       15.00 Mbps     335.40 Mbps    74.40 ms     17.30 ms     
联通 湖南长沙 5G    2.30 Mbps      461.10 Mbps    49.00 ms     3.90 ms      
联通 河南郑州 5G    19.20 Mbps     940.60 Mbps    49.10 ms     8.10 ms      
广电 重庆           0.60 Mbps      31.50 Mbps     86.10 ms     1.20 ms      
教育网 江苏苏州     0.30 Mbps      1.00 Mbps      140.50 ms    37.10 ms     
电信 宿迁 自建        跳过         443.00 Mbps     跳过         跳过        
------------------------------------------------------------------------
当前时间：2023-09-08 09:15:11 CST
北京时间: 2023-09-08 09:15:11+08:00
------------------------------------------------------------------------
```

</details>

<details>

<summary>各大洲 IPV4 八线程测速</summary>
 
✈️ 测试服务器：Hetzner 德国

```
------------------------ 多功能 自更新 测速脚本 ------------------------
 Version               : v2023-09-08
 Usage                 : bash <(curl -sL bash.icu/speedtest)
 GitHub                : https://github.com/i-abc/speedtest
------------------------------------------------------------------------
各大洲 IPv4 八线程测速，v2023-09-08
------------------------------------------------------------------------
测速节点            下载/Mbps      上传/Mbps      延迟/ms      抖动/ms
美国 纽约           1770.00 Mbps   1975.00 Mbps    跳过         跳过        
美国 阿什本         934.00 Mbps    237.00 Mbps     跳过         跳过        
美国 查尔斯顿       1682.00 Mbps   1665.00 Mbps    跳过         跳过        
德国 柏林           13530.00 Mbps  14451.00 Mbps   跳过         跳过        
瑞士 温特图尔       11221.00 Mbps  11167.00 Mbps   跳过         跳过        
丹麦 哥本哈根       6578.00 Mbps   3671.00 Mbps    跳过         跳过        
瑞士 沙夫豪森       9301.00 Mbps   8279.00 Mbps    跳过         跳过        
荷兰 阿姆斯特丹     9271.00 Mbps   9257.00 Mbps    跳过         跳过        
印度 苏里           9330.00 Mbps   9314.00 Mbps    跳过         跳过        
亚洲 新加坡         976.00 Mbps    3.44 Mbps       跳过         跳过        
亚洲 乌兹别克斯坦   1942.00 Mbps   2055.00 Mbps    跳过         跳过        
大洋洲 澳大利亚     164.00 Mbps    398.00 Mbps     跳过         跳过        
大洋洲 新喀里多尼亚 164.00 Mbps    132.00 Mbps     跳过         跳过        
非洲 突尼斯         912.00 Mbps    827.00 Mbps     跳过         跳过        
非洲 毛里求斯       751.00 Mbps    36.40 Mbps      跳过         跳过        
------------------------------------------------------------------------
当前时间：2023-09-08 14:29:19 UTC
北京时间: 2023-09-08 22:29:19+08:00
------------------------------------------------------------------------
```

</details>

<details>

<summary>IPV4 UDP 可用性测试</summary>
 
✈️ 测试服务器：Azure 东京

```
------------------------ 多功能 自更新 测速脚本 ------------------------
 Version               : v2023-09-04
 Usage                 : bash <(curl -sL bash.icu/speedtest)
 GitHub                : https://github.com/i-abc/speedtest
------------------------------------------------------------------------
UDP IPv4 单线程测速，v2023-09-04
机房UDP限速，结果仅代表UDP是否可用
------------------------------------------------------------------------
测速节点            下载/Mbps      上传/Mbps      延迟/ms      抖动/ms
联通/电信 宿迁 自建 1.05 Mbps      1.05 Mbps       跳过         跳过        
美国 阿什本         1.05 Mbps      1.05 Mbps       跳过         跳过        
美国 亚特兰大       1.05 Mbps      1.05 Mbps       跳过         跳过        
美国 查尔斯顿       1.04 Mbps      1.05 Mbps       跳过         跳过        
------------------------------------------------------------------------
当前时间：2023-09-05 20:19:26 CST
北京时间: 2023-09-05 20:19:26+08:00
------------------------------------------------------------------------
```

</details>

<details>

<summary>大陆教育网 IPv4 多线程测速</summary>
 
✈️ 测试服务器：Azure 东京

```
------------------------ 多功能 自更新 测速脚本 ------------------------
 Version               : v2023-09-04
 Usage                 : bash <(curl -sL bash.icu/speedtest)
 GitHub                : https://github.com/i-abc/speedtest
------------------------------------------------------------------------
大陆教育网 IPv4 测速，v2023-09-05
------------------------------------------------------------------------
测速节点            下载/Mbps      上传/Mbps      延迟/ms      抖动/ms
教育网 北京         254.49 Mbps    374.56 Mbps    81.18 ms     0.27 ms      
教育网 上海         245.49 Mbps    273.71 Mbps    200.36 ms    4.05 ms      
教育网 江苏南京     630.06 Mbps    515.28 Mbps    112.09 ms    0.12 ms      
教育网 安徽合肥     0.00 Mbps      641.16 Mbps    105.18 ms    0.37 ms      
------------------------------------------------------------------------
当前时间：2023-09-06 11:21:18 CST
北京时间: 2023-09-06 11:21:18+08:00
------------------------------------------------------------------------
```

</details>

<details>

<summary>大陆教育网 IPv6 多线程测速</summary>
 
✈️ 测试服务器：Hetzner 德国

```
------------------------ 多功能 自更新 测速脚本 ------------------------
 Version               : v2023-09-08
 Usage                 : bash <(curl -sL bash.icu/speedtest)
 GitHub                : https://github.com/i-abc/speedtest
------------------------------------------------------------------------
大陆教育网 IPv6 测速，v2023-09-08
------------------------------------------------------------------------
测速节点            下载/Mbps      上传/Mbps      延迟/ms      抖动/ms
教育网 上海         220.51 Mbps    217.85 Mbps    257.27 ms    0.29 ms      
教育网 江苏南京     210.13 Mbps    156.00 Mbps    260.73 ms    0.46 ms      
教育网 安徽合肥       失败         229.02 Mbps    255.55 ms    1.09 ms      
教育网 辽宁沈阳       失败         8.89 Mbps      241.00 ms     失败        
------------------------------------------------------------------------
当前时间：2023-09-08 14:36:12 UTC
北京时间: 2023-09-08 22:36:12+08:00
------------------------------------------------------------------------
```

</details>

# 使用方法

<a target="_blank" href="https://bash.icu/speedtest"><img src="https://img.shields.io/website?url=https%3A%2F%2Fbash.icu%2Fspeedtest&label=bash.icu%2Fspeedtest&cacheSeconds=300" />

```bash
bash <(curl -sL bash.icu/speedtest)
```

或

```bash
bash <(curl -sL https://raw.githubusercontent.com/i-abc/Speedtest/main/speedtest.sh)
```

仅官方源

```bash
bash <(curl -sL https://raw.githubusercontent.com/iceofrace/Speedtest/main/speedtest.sh)
```

# 基本功能

脚本自带丰富的测试项目：

0. [自定义测速节点](https://github.com/i-abc/Speedtest/tree/main#进阶功能)
1.  大陆三网+教育网 IPv4 多线程测速
2.  大陆三网+教育网 IPv4 单线程测速
3.  大陆教育网 IPv6 多线程测速
4.  各大洲 IPV4 八线程测速
5.  各大洲 IPV6 八线程测速
6.  IPV4 UDP 可用测试测试
7.  大陆教育网 IPv4 多线程测速
8.  大陆电信 IPv4 多线程测速
9.  大陆电信 IPv4 单线程测速
10. 大陆移动 IPv4 多线程测速
11. 大陆移动 IPv4 单线程测速
12. 大陆联通 IPv4 多线程测速
13. 大陆联通 IPv4 单线程测速
14. 各大洲 IPV4 32线程测速
15. 各大洲 IPV4 单线程测速
16. 各大洲 IPV6 32线程测速
17. 各大洲 IPV6 单线程测速

持续更新中……

# 进阶功能

自定义自己想要的测试项目，很简单的。

我们会有两张表，节点表 (必需)、节点集合表 (非必需)。

## 节点表 (必需)

节点表分为四个区域，分别是提示语区、测试类型区、节点名区、测试参数区；后三区组成三列，彼此之间用英文逗号 `,` 分隔，如下图所示：

![](https://github.com/i-abc/Speedtest/raw/main/images/1.png)

### 示例

```
节点表 模板示例，v2023-09-08
speedtest-cli ,联通 郑州 cli       ,-o 5gtest.shangdu.com
bim-core      ,联通 郑州 bimc      ,http://5gtest.shangdu.com:8080/download http://5gtest.shangdu.com:8080/upload
speedtest-go  ,联通 郑州 go        ,--custom-url http://5gtest.shangdu.com:8080/speedtest/upload.php --ping-mode http
speedtest-go  ,联通 郑州 八线程    ,--custom-url http://5gtest.shangdu.com:8080/speedtest/upload.php --ping-mode http -t 8
speedtest-go  ,联通 郑州 只测上传  ,--custom-url http://5gtest.shangdu.com:8080/speedtest/upload.php --ping-mode http --no-download
librespeed-cli,教育 南京           ,--server-json https://jihulab.com/i-abc/speedtest/-/raw/node/china-education.json --server 1 --no-icmp
librespeed-cli,教育 南京 只测上传  ,--server-json https://jihulab.com/i-abc/speedtest/-/raw/node/china-education.json --server 1 --no-icmp --no-download
iperf3        ,联通 宿迁 只测上传  ,-c 103.239.244.210 -p 22222
iperf3        ,联通 宿迁 只测下载  ,-c 103.239.244.210 -p 22222 -R
iperf3        ,联通 宿迁 八线程    ,-c 103.239.244.210 -p 22222 -P 8
iperf3        ,联通 宿迁 测UDP     ,-c 103.239.244.210 -p 22222 -u
iperf3        ,联通 宿迁 测双向    ,-c 103.239.244.210 -p 22222 --up-and-down
```

### 1区：提示语区 (可选)

提示语位于节点表开头，可以在这里写上任何话，比如使用说明、备注、自家广告等，当然也可以不写。

### 3区：节点名区

显而易见，这里就是写对应节点的名字。

由于中英文字符编码很难处理，所以如果想要输出美观还得麻烦大家敲空格对齐，当然不对齐对测试无影响。

提示语区、节点名区会直接反映到输出，它们在输出、节点表之间的关系如下图所示：

![](https://github.com/i-abc/Speedtest/raw/main/images/2.png)

### 2区：测试类型区

我们有五种类型，分别是 [speedtest-cli](https://www.speedtest.net/zh-Hans/apps/cli)、[bim-core](https://github.com/veoco/bim-core)、[speedtest-go](https://github.com/showwin/speedtest-go)、[librespeed-cli](https://github.com/librespeed/speedtest-cli)、[iperf3](https://github.com/esnet/iperf)，选一种即可，每种都有不同的特点，具体说明请往下看。

这部分加空格对齐不是必须的，不加对输出无任何影响，当然像我一样的强迫症可以加空格对齐。

### 4区：测试参数区

我们脚本兼容 [speedtest-cli](https://www.speedtest.net/zh-Hans/apps/cli)、[bim-core](https://github.com/veoco/bim-core)、[speedtest-go](https://github.com/showwin/speedtest-go)、[librespeed-cli](https://github.com/librespeed/speedtest-cli)、[iperf3](https://github.com/esnet/iperf)，我挑选了部分对测试有用的参数应用到了脚本里，大家可以按需使用。

| **类型**         | **测速点提供商**    | **只单向测速** | **指定IPv6测速** | **单连接测速** | **UDP测试** | **不使用 ICMP Ping** | **指定测试时长** |
|----------------|---------------|-----------|---------------|-----------|-----------|-------------------|---------------|
| speedtest-cli  | speedtest.net | ❌         | ❌             | ❌         | ❌         | ❌                 | ❌             |
| bim-core       | speedtest.net | ❌         | ✔️            | ✔️        | ❌         | ❌                 | ❌             |
| speedtest-go   | speedtest.net | ✔️        | ❌             | ✔️        | ❌         | ✔️                | ❌             |
| librespeed-cli | 公共、自建         | ✔️        | ✔️            | ❌         | ❌         | ✔️                | ✔️            |
| iperf3         | 公共、自建         | ✔️        | ✔️            | ✔️        | ✔️        | ❌                 | ✔️            |

**使用 [speedtest.net](https://www.speedtest.net) 时，多连接测速推荐 speedtest-cli、单连接测速推荐 bim-core。**

#### 1️⃣ speedtest-cli

[speedtest-cli](https://www.speedtest.net/zh-Hans/apps/cli)：[speedtest.net](https://www.speedtest.net) 官方 CLI，功能单一。

 | 参数 | 作用         | 示例                    |
|----|------------|-----------------------|
| -s value | 通过 id 指定节点 | -s 36646              |
| -o value | 通过域名指定节点   | -o 5gtest.shangdu.com |

`-s` 和 `-o` 二选一，`-o` 后面参数为纯域名，不含 http(s)、端口号；推荐 `-o`。

节点 id、域名可在 [https://www.speedtest.net/api/ios-config.php](https://www.speedtest.net/api/ios-config.php) 查阅。

例如：`<server url="http://5gtest.shangdu.com:8080/speedtest/upload.php" lat="34.3287" lon="109.0337" name="Zhengzhou" sponsor="China Unicom HeNan 5G" id="36646" />`，则 id 为 `36646`，域名为 `5gtest.shangdu.com`。

#### 2️⃣ bim-core

[bim-core](https://github.com/veoco/bim-core)：针对 [speedtest.net](https://www.speedtest.net) 开发的第三方，功能较多，能实现单线程、指定 IPv6 测速。

| 参数                | 作用                         | 示例                                                               |
|-------------------|----------------------------|------------------------------------------------------------------|
| download_url        | 节点的下载链接           | http://5gtest.shangdu.com:8080/download                         |
| upload_url | 节点的上传链接              | http://5gtest.shangdu.com:8080/upload |
| -m                | 启用八线程测速                   | -m                                                               |
| -6     | 仅使用 IPv6                     | -6                                                    |

download_url 和 upload_url 两者都要，且 download_url 在前、upload_url 在后，含 http(s)、端口、分别以 `/download`、`/upload` 结尾。

节点链接可在 [https://www.speedtest.net/api/ios-config.php](https://www.speedtest.net/api/ios-config.php) 查阅。

例如：`<server url="http://5gtest.shangdu.com:8080/speedtest/upload.php" lat="34.3287" lon="109.0337" name="Zhengzhou" sponsor="China Unicom HeNan 5G" id="36646" />`，则 download_url 为 `http://5gtest.shangdu.com:8080/download`，则 upload_url 为 `http://5gtest.shangdu.com:8080/upload`。

#### 3️⃣ speedtest-go

[speedtest-go](https://github.com/showwin/speedtest-go)：针对 [speedtest.net](https://www.speedtest.net) 开发的第三方，功能较多，能实现指定线程、禁用某方向测速。

| 参数                | 作用                         | 示例                                                               |
|-------------------|----------------------------|------------------------------------------------------------------|
| -s value        | 通过 id 指定节点           | -s 36646                                                         |
| --custom-url value | 通过链接指定节点              | --custom-url http://5gtest.shangdu.com:8080/speedtest/upload.php |
| -t value          | 设置并发连接数                   | -t 8                                                             |
| -m                | 启用多服务器模式                   | -m                                                               |
| --no-download     | 禁用下载测试                     | --no-download                                                    |
| --no-upload       | 禁用上传测试                     | --no-upload                                                      |
| --ping-mode value | 选择一种 Ping 的方法 | --ping-mode http                                                |

`-s` 和 `--custom-url` 二选一，`--custom-url` 后面参数为完整链接，含 http(s)、端口、以 `/upload.php` 结尾；推荐 `--custom-url`。

`--ping-mode http` 推荐加上。

节点 id、链接可在 [https://www.speedtest.net/api/ios-config.php](https://www.speedtest.net/api/ios-config.php) 查阅。

例如：`<server url="http://5gtest.shangdu.com:8080/speedtest/upload.php" lat="34.3287" lon="109.0337" name="Zhengzhou" sponsor="China Unicom HeNan 5G" id="36646" />`，则 id 为 `36646`，链接为 `http://5gtest.shangdu.com:8080/speedtest/upload.php`。

#### 4️⃣ librespeed-cli

[librespeed-cli](https://github.com/librespeed/speedtest-cli)

| 参数            | 作用                                            | 示例                                                                                |
|---------------|-----------------------------------------------|-----------------------------------------------------------------------------------|
| --server-json value | 远程 JSON 的服务端列表                                | --server-json https://jihulab.com/i-abc/speedtest/-/raw/node/china-education.json |
| --local-json value | 本地 JSON 的服务端列表                                | --local-json /root/librespeed.json                                                |
| --server value     | 通过 JSON 中的 ID 指定服务端                           | --server 1                                                                        |
| -4            | 仅使用 IPv4 (默认 false)                           | -4                                                                                |
| -6            | 仅使用 IPv6 (默认 false)                           | -6                                                                                |
| --no-download | 禁用下载测试 (默认 false)                             | --no-download                                                                     |
| --no-upload   | 禁用上传测试 (默认 false)                             | --no-upload                                                                       |
| --no-icmp     | 不使用 ICMP Ping。ICMP 在 Linux 下工作不稳定 (默认 false) | --no-icmp                                                                         |
| --duration    | 测试的持续时间 (秒) (默认 15)                          | --duration 20                                                                     |

`--no-icmp` 推荐加上。

现成的、优质的 librespeed 服务端较少，而且需要自己写服务端列表 JSON，JSON 写法参照 [官方](https://github.com/librespeed/speedtest-cli#use-a-custom-backend-server-list)；如果是个人搭建测速、个人使用，推荐 iperf3。

#### 5️⃣ iperf3

[iperf3](https://github.com/esnet/iperf)

| 参数            | 作用                  | 示例                 |
|---------------|---------------------|--------------------|
| -c ip/host    | 指定服务端               | -c 103.239.244.210 |
| -p value      | 指定服务端端口             | -p 22222           |
| -P value      | 设置并发连接数             | -P 8               |
| -t value      | 测试的持续时间 (秒) (默认 10) | -t 20              |
| -O value      | 前 N 秒的数据不计入最终结果     | -O 3               |
| -R            | 反向模式，服务器发送、客户端接收    | -R                 |
| -4            | 仅使用 IPv4            | -4                 |
| -6            | 仅使用 IPv6            | -6                 |
| -u            | UDP测试               | -u                 |
| --up-and-down | 双向测试 (自创选项)       | --up-and-down      |

当服务端端口为默认的 5201 时，`-p` 可不加；`-p` 除了 `-p 22222` 指定一个端口，还能 `-p 5200-5209` 指定一个范围内的端口。

iperf3 默认是客户端发送、服务端接收，也就是测上传；想测下载可加 `-R` 开启反向模式；但 iperf3 只支持单向，所以脚本里自创了 `--up-and-down` 选项，加上后可测双向；`--up-and-down` 与 `-R` 二选一，**且 `--up-and-down` 在本脚本以外的地方不可用，非官方选项**。

现成的、优质的 iperf3 服务端很多，可在 [iPerf3 Server List](https://iperf3serverlist.net) 查阅；自建 iperf3 服务端也简单，用包管理器就行了。

## 节点集合表 (非必需)

当你有很多节点表时可以组一个节点表合集，如下图所示，当然这不是必需的。

![](https://github.com/i-abc/Speedtest/raw/main/images/3.png)

### 示例

```
1. 节点示例
/root/GitHub/speedtest/node-template-1.txt
2. 示例1
/root/GitHub/speedtest/node-template-01.txt
3. 示例2
/root/GitHub/speedtest/node-template-02.txt
```

每两行为一组，每组中的第一行以序号加英文点 `.` 开头，第二行为节点表链接，链接可为远程 http 或本地绝对路径。

节点集合表与输出之间的关系如下图所示：

![](https://github.com/i-abc/Speedtest/raw/main/images/5.png)

## 使用自定义的表

我们现在有了节点表、节点集合表，那么该如何使用呢？

只需选择时输入序号 `0`，然后填写链接或本地绝对路径即可；链接为节点表就立即开始测试，链接为节点集合表就还会出现选择节点的提示。

![](https://github.com/i-abc/Speedtest/raw/main/images/6.png)
