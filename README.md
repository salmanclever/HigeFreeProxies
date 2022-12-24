# HigeFreeProxies
[![GitHub Workflow Status](https://github.com/baipiao250/HigeFreeProxies/actions/workflows/get-proxies.yml/badge.svg)](https://github.com/baipiao250/HigeFreeProxies/actions/workflows/get-proxies.yml) 

![Watchers](https://img.shields.io/github/watchers/baipiao250/HigeFreeProxies) ![Stars](https://img.shields.io/github/stars/baipiao250/HigeFreeProxies) ![Forks](https://img.shields.io/github/forks/baipiao250/HigeFreeProxies) ![Vistors](https://visitor-badge.laobi.icu/badge?page_id=baipiao250.HigeFreeProxies) ![LICENSE](https://img.shields.io/badge/license-CC%20BY--SA%204.0-green.svg)

[仓库介绍](https://github.com/baipiao250/HigeFreeProxies#仓库介绍) | [使用方法](https://github.com/baipiao250/HigeFreeProxies#使用方法) | [节点信息](https://github.com/baipiao250/HigeFreeProxies#节点信息) | [软件推荐](https://github.com/baipiao250/HigeFreeProxies#客户端选择) | [仓库声明](https://github.com/baipiao250/HigeFreeProxies#仓库声明)

## 仓库介绍
本仓库自动化功能全部基于 `GitHub Actions` 实现，如有需要可以自行 Fork 实现个性化需求，功能配置在 `./utils/config.ini` 配置文件中。

对网络上各免费节点池及博主分享的节点进行测速筛选出较为稳定高速的节点，再导入到仓库中进行分享记录。所筛选的节点链接在仓库 `./sub/sub_list.json` 文件中，其中大部分为其他 `GitHub` 仓库链接，如果大家有好的订阅链接欢迎提交 PR ，这些链接包含的所有节点会合并在仓库 `./sub/sub_merge.txt` 中。

测速筛选后的节点订阅文件在仓库根目录 `Eterniy`(Base64) 和 `Eternity.yaml`(Clash)。同时在仓库的 `./update` 中保留了原始节点链接的的记录。

订阅转换使用 [subconverter](https://github.com/tindy2013/subconverter) 实现，测速功能使用 [LiteSpeedTest](https://github.com/xxf098/LiteSpeedTest) 在 `GitHub Actions` 环境下实现，所以美国节点较多，不能很好代表国内网络环境下节点可用性，目前正在解决这一问题。

虽然是测速筛选过后的节点，但仍然会出现部分节点不可用的情况，遇到这种情况建议选择`Clash`, `Shadowrocket`之类能自动切换低延迟节点的客户端。

## 使用方法
将以下订阅链接导入相应客户端即可。链接中大部分为 SS 协议节点，少量 Vmess, Trojan ,SSR 协议节点，建议选择协议支持完整的客户端。

- [多协议Base64编码](https://raw.githubusercontent.com/baipiao250/HigeFreeProxies/master/Eternity)
- [Clash](https://raw.githubusercontent.com/baipiao250/HigeFreeProxies/master/Eternity.yaml)

另有国内加速链接：

- [多协议Base64编码](https://fastly.jsdelivr.net/gh/baipiao250/HigeFreeProxies@master/Eternity)
- [Clash](https://fastly.jsdelivr.net/gh/baipiao250/HigeFreeProxies@master/Eternity.yaml)

>`Clash`链接所使用的配置在仓库`./update/provider/`中，有相应配置文件和以国家分类的`proxy-provider`。
>
>需要其它配置可使用订阅转换工具自行转换。
>自用在线订阅转换网址：[sub-web-modify](https://sub.v1.mk/)

## 节点信息
### 高速节点
高速节点数量: `94`
<details>
  <summary>展开复制节点</summary>

    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@3.112.193.151:443#%F0%9F%87%AF%F0%9F%87%B5%20_JP_%E6%97%A5%E6%9C%AC%209
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.201.86.30:443#%F0%9F%87%B0%F0%9F%87%B7%20_KR_%E9%9F%A9%E5%9B%BD_3
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.201.57.66:443#%F0%9F%87%B0%F0%9F%87%B7%20_KR_%E9%9F%A9%E5%9B%BD_1
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzEyMjM0MjciLCJhZGQiOiJ2MjYuaWRjbG91ZGhvc3QuZGUiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiZDdhNzUzMTgtMzU4MS00ZjE2LTkzNmMtNjcxOTM3ZGRkOGVkIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoidG1zLmRpbmd0YWxrLmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzEyMjMzOTYiLCJhZGQiOiIxNS4yMzUuMTkyLjE5NiIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiIzNzAxZGVkMy0wOWJhLTQxNTQtOTcwZC1hOWY0YTA5MGEzODIiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3ZtZXNzIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzEyMjMwMTgiLCJhZGQiOiIxOC4xNDMuMTIzLjM1IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjY4ZGY0ODM4LTQ2ZDAtNGI1Yi1jM2YwLWE0MGVjNzA2MzI0NSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzEyMjMzMzMiLCJhZGQiOiJhZ3JvdXAubm9kZTMudi5ub2RlbGlzdC1nZndhaXJwb3J0MS5kb3dubG9hZCIsInBvcnQiOiI1MDAwMSIsInR5cGUiOiJub25lIiwiaWQiOiI0NTI3ZmU0ZS0wY2I0LTQ4NmMtYTRlMC1lN2Y1OGZmMDQzOTYiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiYWdyb3VwLm5vZGUzLnYubm9kZWxpc3QtZ2Z3YWlycG9ydDEuZG93bmxvYWQiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7Ag6aaZ5rivXzEyMjM0NTciLCJhZGQiOiI4LjIxOC4zLjEyIiwicG9ydCI6IjIwODIiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzZmYTQ1ZGItMmQ0YS00Mjk1LWExZmUtMjIzODM2OTg5ODc4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9waW5lYXBwbGUiLCJob3N0IjoiUGluZUFwcGxlLkNMT1VERkxBUkUuUVVFU1QiLCJ0bHMiOiIifQ==
    ss://YWVzLTI1Ni1nY206ekROVmVkUkZQUWV4Rzl2@139.99.68.21:6379#%F0%9F%87%B8%F0%9F%87%AC%20TG%40hkaa0%7C%E6%96%B0%E5%8A%A0%E5%9D%A1%207
    ss://YWVzLTI1Ni1nY206Y2RCSURWNDJEQ3duZklO@85.208.108.94:8119#%F0%9F%87%AF%F0%9F%87%B5%20TG%40hkaa0%7C%E6%97%A5%E6%9C%AC
    ss://YWVzLTI1Ni1nY206VEV6amZBWXEySWp0dW9T@85.208.108.20:6697#%F0%9F%87%AF%F0%9F%87%B5%20TG%40hkaa0%7C%E6%97%A5%E6%9C%AC%2016
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@85.208.108.18:5001#%F0%9F%87%AF%F0%9F%87%B5%20TG%40hkaa0%7C%E6%97%A5%E6%9C%AC%2017
    ss://YWVzLTI1Ni1nY206Rm9PaUdsa0FBOXlQRUdQ@85.208.108.93:7306#%F0%9F%87%AF%F0%9F%87%B5%20TG%40hkaa0%7C%E6%97%A5%E6%9C%AC%2019
    ss://YWVzLTI1Ni1nY206UENubkg2U1FTbmZvUzI3@85.208.108.58:8090#%F0%9F%87%AF%F0%9F%87%B5%20TG%40hkaa0%7C%E6%97%A5%E6%9C%AC%2014
    trojan://HKZmLDgP@hk2.openssl3.com:15006?allowInsecure=1#%F0%9F%87%AD%F0%9F%87%B0%20_HK_%E9%A6%99%E6%B8%AF_2
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cgS1LjgJDku5jotLnmjqjojZDvvJpnb28uZ3Mvdmlw44CRIiwiYWRkIjoic3Vyb25nd2VpLmV1Lm9yZyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjA5M2VlZmItN2FiNi00MWRmLWFiYTAtZDVmYTU4MTQ3ZTEwIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9yZWZmczd5MjZnMHVhIiwiaG9zdCI6InN1cm9uZ3dlaS5ldS5vcmciLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1jZmI6MWU1MTExNjk5YzQ1NDk2ZGE4NDExMmYzNWRiNjY1YzQ@165.232.169.142:29332#%F0%9F%87%B8%F0%9F%87%AC%20TG%40hkaa0%7C%E6%96%B0%E5%8A%A0%E5%9D%A1%208
    trojan://b291d129-ee55-4801-a9b8-b5316e5c37b7@jgwcc3.gaox.ml:443?allowInsecure=0#%F0%9F%87%B0%F0%9F%87%B7%20TG%40hkaa0%7C%E9%9F%A9%E5%9B%BD%206
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cg6Z+p5Zu9XzEyMjMwODEiLCJhZGQiOiIxMDMuMTM4LjgwLjE5MyIsInBvcnQiOiIxNDQ4NSIsInR5cGUiOiJub25lIiwiaWQiOiJiNjg3Yjk3NC03MDFiLTRhN2ItZTdhNC1jN2Y4YjUxMDI3MjMiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgLeaWsOWKoOWdoS1hd3NzZzIuamlhc3ViLnh5eiIsImFkZCI6ImF3c3NnMi5qaWFzdWIueHl6IiwicG9ydCI6IjQwMDAyIiwidHlwZSI6Im5vbmUiLCJpZCI6IjNmZTU3YzYxLTYyNTUtMzdkNC1iMzRiLTM2OTViNjU2YTJiMSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6ImF3c3NnMi5qaWFzdWIueHl6IiwidGxzIjoiIn0=
    ssr://NDIuOTguMjcuMTgzOjU0MzphdXRoX2FlczEyOF9tZDU6Y2hhY2hhMjAtaWV0ZjpwbGFpbjpiV0pzWVc1ck1YQnZjblEvP2dyb3VwPVUxTlNVSEp2ZG1sa1pYSSZyZW1hcmtzPThKLUhyZkNmaDdBZ0xlbW1tZWE0cnkwME1pNDVPQzR5Tnk0eE9ETSZvYmZzcGFyYW09JnByb3RvcGFyYW09TlRFek5qRTZOamR0WmtsVWIwdzRORkJ1V25Fd1pB
    ssr://aGs1LnZmdW4uaWN1OjQ0MzphdXRoX2FlczEyOF9zaGExOmFlcy0yNTYtY2ZiOnBsYWluOmRubDFibTFsLz9ncm91cD1VMU5TVUhKdmRtbGtaWEkmcmVtYXJrcz04Si1Icl9DZmg3VWdMZWFYcGVhY3JDMW9helV1ZG1aMWJpNXBZM1Umb2Jmc3BhcmFtPSZwcm90b3BhcmFtPU1UWTVOVEk2T1dKcGF6aEo
    ssr://anAuaW5kaWdvLjAyLm5la29jbG91ZC5jbjoxOTA1OTphdXRoX2FlczEyOF9tZDU6YWVzLTEyOC1jZmI6cGxhaW46YVd4MWRXeHllblpwYVdzLz9ncm91cD1VMU5TVUhKdmRtbGtaWEkmcmVtYXJrcz04Si1Icl9DZmg3VWdMZWFYcGVhY3JDMXFjQzVwYm1ScFoyOHVNREl1Ym1WcmIyTnNiM1ZrTG1OdSZvYmZzcGFyYW09TW1NME5tSTBNall4TXk1M2JuTXVkMmx1Wkc5M2N5NWpiMjAmcHJvdG9wYXJhbT0
    ssr://c2ctYW0zLmVxc3Vuc2hpbmUuY29tOjMyMDAxOm9yaWdpbjphZXMtMjU2LWNmYjp0bHMxLjJfdGlja2V0X2F1dGg6TTJjd1pFaHNTMDFGLz9ncm91cD1VMU5TVUhKdmRtbGtaWEkmcmVtYXJrcz04Si1IdVBDZmg2d2dMZWFXc09XS29PV2RvUzF6WnkxaGJUTXVaWEZ6ZFc1emFHbHVaUzVqYjIwJm9iZnNwYXJhbT0mcHJvdG9wYXJhbT0
    trojan://4a884efc-5738-4470-9494-f7cf783a79ab@cn-hk-30.fnhffffe4.cc:50046?allowInsecure=0#%F0%9F%87%AD%F0%9F%87%B0%20%5B12-24%5D-%F0%9F%87%AD%F0%9F%87%B0-%E9%A6%99%E6%B8%AF-7254-cn-hk-30.fnhffffe4.cc
    trojan://4c7985e0-79e8-11eb-b8d3-1239d0255272@sg3-trojan.bonds.id:443?allowInsecure=0#%F0%9F%87%B8%F0%9F%87%AC%20%5B12-24%5D-%F0%9F%87%B8%F0%9F%87%AC-%E6%96%B0%E5%8A%A0%E5%9D%A1-6695-sg3-trojan.bonds.id
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cgLemfqeWbvS0wMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAzN2Eubm9kZS1mb3ItYmlnYWlycG9ydC53aW4iLCJhZGQiOiIwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAzN2Eubm9kZS1mb3ItYmlnYWlycG9ydC53aW4iLCJwb3J0IjoiMTIzNTYiLCJ0eXBlIjoibm9uZSIsImlkIjoiZjNmZGEwYzYtNDAyNS00ZGE3LTgyYjQtODg0MjNkOWVjNDg5IiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IjAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDM3YS5ub2RlLWZvci1iaWdhaXJwb3J0LndpbiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgLeaWsOWKoOWdoS0xMDMuMjUzLjI2LjIyMyIsImFkZCI6IjEwMy4yNTMuMjYuMjIzIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjFkMmZiODAwLTdmZjMtMTFlZC1iMDMzLTIwNWM2ZDVmNWQ3OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6Inpvb20udXMiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgLemmmea4ry0xMDMuMjAwLjExMi4xODEiLCJhZGQiOiIxMDMuMjAwLjExMi4xODEiLCJwb3J0IjoiNjIyNzUiLCJ0eXBlIjoibm9uZSIsImlkIjoiYTgyYjcxOTItYTIwOS00NTc1LWExNjMtMWU4MGM2MGMxODczIiwiYWlkIjoiMCIsIm5ldCI6Imh0dHAiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgLeaXpeacrC0xNzIuMTA1LjE5Mi4yMyIsImFkZCI6IjE3Mi4xMDUuMTkyLjIzIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjhkZGIzMWYxLTZiMGYtM2FiYi05OTRlLWQ2MzE2ZDc1NTMxMCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgLeaWsOWKoOWdoS0xOXhqcC5tZWFsc3RyZWFtLnh5eiIsImFkZCI6IjE5eGpwLm1lYWxzdHJlYW0ueHl6IiwicG9ydCI6IjE1MzE5IiwidHlwZSI6Im5vbmUiLCJpZCI6IjFmN2MwMDJmLTdmMTUtNDVkNC05ZDA3LWRhZTI2MzY2NjA4NyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIxOXhqcC5tZWFsc3RyZWFtLnh5eiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgLemmmea4ry0yOS5kb3VsdW8uYmVhdXR5IiwiYWRkIjoiMjkuZG91bHVvLmJlYXV0eSIsInBvcnQiOiI1NjEyOSIsInR5cGUiOiJub25lIiwiaWQiOiIzMGQxMmE3Zi02ZDVlLTMxNDEtYTczMi1jYTZkODNhMTkyY2QiLCJhaWQiOiIyIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMjkuZG91bHVvLmJlYXV0eSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgLemmmea4ry00Ny4yNDIuMTQ2LjEyMyIsImFkZCI6IjQ3LjI0Mi4xNDYuMTIzIiwicG9ydCI6IjI2MjM3IiwidHlwZSI6Im5vbmUiLCJpZCI6ImM4ZjVhNWZkLTBhNjktNGNmNi04ZmE2LTJlYTAyMTcxZDZhMyIsImFpZCI6IjAiLCJuZXQiOiJodHRwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgLemmmea4ry00Ny4yNDMuMjMuODAiLCJhZGQiOiI0Ny4yNDMuMjMuODAiLCJwb3J0IjoiMjAyNTYiLCJ0eXBlIjoibm9uZSIsImlkIjoiZjcwN2ZkMDgtZjAxNy00YjliLWFlYWUtZGE5MDhiMzRlMzEzIiwiYWlkIjoiMCIsIm5ldCI6Imh0dHAiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgLemmmea4ry00Ny4yNDMuNzIuNzYiLCJhZGQiOiI0Ny4yNDMuNzIuNzYiLCJwb3J0IjoiODQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIzZmU1N2M2MS02MjU1LTM3ZDQtYjM0Yi0zNjk1YjY1NmEyYjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiI0Ny4yNDMuNzIuNzYiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgLeaXpeacrC1hbWQxLnhsci1tbC5tbCIsImFkZCI6ImFtZDEueGxyLW1sLm1sIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6ImZiOTFlMWQ3LTQ0MGUtNDQ3MC1iMGEwLWE3OTFlNWMzMmRjOCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6ImEuMTg5LmNuIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wgLeaWsOWKoOWdoS1hd3NzZzEuamlhc3ViLnh5eiIsImFkZCI6ImF3c3NnMS5qaWFzdWIueHl6IiwicG9ydCI6IjQwMDAyIiwidHlwZSI6Im5vbmUiLCJpZCI6IjNmZTU3YzYxLTYyNTUtMzdkNC1iMzRiLTM2OTViNjU2YTJiMSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6ImF3c3NnMS5qaWFzdWIueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7MgLeWPsOa5vuahg+WbreW4gi1kMDQxYTU4NS0wYzFlLWU5MjgtZGZiYi1jNWM0YmI3Zjk2ODUuY25uaWMucmlwIiwiYWRkIjoiZDA0MWE1ODUtMGMxZS1lOTI4LWRmYmItYzVjNGJiN2Y5Njg1LmNubmljLnJpcCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJmYzQ1OTUzMy1mOGQ5LTQxMDctOGFiNS1kODZkNjJiOTcwNjQiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJZb3VUdWJlLWF3ZWlrZWppIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgLemmmea4ry1oazEudnBuamFudGl0LmNvbSIsImFkZCI6ImhrMS52cG5qYW50aXQuY29tIiwicG9ydCI6IjEwMDAwIiwidHlwZSI6Im5vbmUiLCJpZCI6ImRmOWMxZmYwLTRkYjktMTFlZC04YTNmLTAwMTYzZTAxOWU2ZSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6ImhrMS52cG5qYW50aXQuY29tIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgLemmmea4ry1oazIubmV0ZmxpeDYuY29tIiwiYWRkIjoiaGsyLm5ldGZsaXg2LmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiM2NjMTEwNjItN2VmYi0zZWNlLWE2YzAtMGRkMTQzOWM0Nzc0IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiaGsyLm5ldGZsaXg2LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgLeaXpeacrOS4nOS6rC1qcDUubG92aW5nMTIzLmNsb3VkIiwiYWRkIjoianA1LmxvdmluZzEyMy5jbG91ZCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJhNmU4ZjkxMS0wMmI4LTQzY2EtYThmYy01MWE3OWQ5ZmFlNDgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJqcDMuY29uZ3JhaW4udG9wIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgLeaXpeacrC1qcDguY3pzMTAwMC5jb20iLCJhZGQiOiJqcDguY3pzMTAwMC5jb20iLCJwb3J0IjoiMjA4OTMiLCJ0eXBlIjoibm9uZSIsImlkIjoiODliZGU0NTktY2RiOS00NTk4LWJlZTctYTI4MjM5MTllOTBiIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6ImpwMy5jb25ncmFpbi50b3AiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgLeaXpeacrC1qcC1hLnRlbmNlbnQuY2ZkIiwiYWRkIjoianAtYS50ZW5jZW50LmNmZCIsInBvcnQiOiI2NTUyOCIsInR5cGUiOiJub25lIiwiaWQiOiI0ZWFhNzAzNi00MjA5LTRiYTUtYTQwNC1iY2RlYjY4ZTUwNGUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJqcC1hLnRlbmNlbnQuY2ZkIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgLeaXpeacrC1qcC1hLnRlbmNlbnQuY2ZkIDIiLCJhZGQiOiJqcC1hLnRlbmNlbnQuY2ZkIiwicG9ydCI6IjY1NTI4IiwidHlwZSI6Im5vbmUiLCJpZCI6IjdhOGEyMTU4LWVkNjItNDM2NC04YmE5LTkzN2YwYWI5ZDZmMCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6ImpwLWEudGVuY2VudC5jZmQiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgLeaXpeacrOS4nOS6rC1qcDAyLjE3MDIwMy54eXoiLCJhZGQiOiJqcDAyLjE3MDIwMy54eXoiLCJwb3J0IjoiMjMyNDUiLCJ0eXBlIjoibm9uZSIsImlkIjoiMjYxNmIzNTMtNGZjYi00NDRhLWIyYzAtNjE1MjFkMTFhY2ZjIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoianAwMi4xNzAyMDMueHl6IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS05Q0ROIiwiYWRkIjoiMTg1LjE2Mi4yMjguMjI4IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6ImxnMS50cnVtcDIwMjMudXMiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzEyMjMwOTgiLCJhZGQiOiJibG9nLnZvZXdsLmNvbSIsInBvcnQiOiI0MzgxNSIsInR5cGUiOiJub25lIiwiaWQiOiI3YTlmMDI2Zi1mN2E4LTQwY2EtZjJmOS0zYjM4MGMyODdjMGQiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2FiYyIsImhvc3QiOiJibG9nLnZvZXdsLmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMkNETiIsImFkZCI6IjE5MC45My4yNDQuMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDBkNDk2YTYtY2VlYi00MDk2LWJhZWItNGNjNTJiMjA1NjIxIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9FQ1RDSjBERiIsImhvc3QiOiJsZzEudHJ1bXAyMDIzLnVzIiwidGxzIjoidGxzIn0=
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@52.13.16.81:443#%F0%9F%87%BA%F0%9F%87%B8%20_US_%E7%BE%8E%E5%9B%BD_1
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0yQ0ROIiwiYWRkIjoiMTg4LjExNC45OS4xMSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xMENETiIsImFkZCI6IjE0MS4xMDEuMTE0LjMyIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0yQ0ROIiwiYWRkIjoiMTg4LjExNC45OS4xMCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMENETiIsImFkZCI6IjE0MS4xMDEuMTE1LjMwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6ImxnMS50cnVtcDIwMjMudXMiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My05Q0ROIiwiYWRkIjoiMTg1LjE2Mi4yMjguMjMwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0zQ0ROIiwiYWRkIjoiMjMuMjI3LjM4LjM5IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI1NmEyMTg4Yi0yYWI3LTQwMmMtYjliOC0zNDg0N2ZkZjA5NTgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzVRTlJPU1JWIiwiaG9zdCI6Im9wbGcxLnpodWppY24yLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xM0NETiIsImFkZCI6IjE5MC45My4yNDUuMyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0zQ0ROIiwiYWRkIjoiMjMuMjI3LjM4LjQwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My04Q0ROIiwiYWRkIjoiNjYuMjM1LjIwMC4yMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My03Q0ROIiwiYWRkIjoiMjAzLjI0LjEwOC4xMCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9KFRH6aKR6YGTQGt4c3dhKSA1IiwiYWRkIjoiY2YtbHQuc2hhcmVjZW50cmUub25saW5lIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyMGU5Mjg4MS01ZmI0LTRiMDUtYmM3Ny01NzkyOTQ3NmRjNjkiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3NoaXJrZXIiLCJob3N0IjoiaGsuc2hhcmVjZW50cmUub25saW5lIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xM0NETiIsImFkZCI6IjE5MC45My4yNDQuNCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xNENETiIsImFkZCI6IjE5MC45My4yNDYuMyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xNENETiIsImFkZCI6IjE5MC45My4yNDYuNCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi02Q0ROIiwiYWRkIjoiMjAzLjMwLjE4OC4xODkiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjU2YTIxODhiLTJhYjctNDAyYy1iOWI4LTM0ODQ3ZmRmMDk1OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvNVFOUk9TUlYiLCJob3N0Ijoib3BsZzEuemh1amljbjIuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggLee+juWbvS0xMzcuMTc1LjI4LjUiLCJhZGQiOiIxMzcuMTc1LjI4LjUiLCJwb3J0IjoiMTc4MDUiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzAyOTdhYjItY2VlZi00OGFlLTgzOGYtOWNhNGJmNjI1ZGE4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xMENETiIsImFkZCI6IjE4NS4xNjIuMjI4LjIyOSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1nY206ZTRGQ1dyZ3BramkzUVk@38.86.135.36:9101#%F0%9F%87%BA%F0%9F%87%B8%20TG%40hkaa0%7C%E7%BE%8E%E5%9B%BD%2057
    ss://YWVzLTI1Ni1nY206ZTRGQ1dyZ3BramkzUVk@38.86.135.169:9101#%F0%9F%87%BA%F0%9F%87%B8%20TG%40hkaa0%7C%E7%BE%8E%E5%9B%BD%20133
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@38.107.226.238:2375#%F0%9F%87%BA%F0%9F%87%B8%20TG%40hkaa0%7C%E7%BE%8E%E5%9B%BD%20116trojan%2F%2F05742120-ce23-4cc8-88f5-6d221ce45bf4%40fhcarm1.gaox.ml443%3FallowInsecure%3D0%23%7C21.48Mb
    trojan://9f547d14-f92a-4324-bf6b-bc958ab05eb1@us-la-41.fnhffffe4.cc:50230?allowInsecure=1#mianfeifq%20139
    trojan://dbf9bf9c-2c3f-474a-8031-d4c00666a989@fhcamd2.gaox.ml:443?allowInsecure=0#%7C22.52Mb
    trojan://shefelnak@content-provider21.cdn-delivery.akamaicd.com:443?allowInsecure=1#mianfeifq%20107
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xNENETiAyIiwiYWRkIjoiMTkwLjkzLjI0Ni4zIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI1NmEyMTg4Yi0yYWI3LTQwMmMtYjliOC0zNDg0N2ZkZjA5NTgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzVRTlJPU1JWIiwiaG9zdCI6Im9wbGcxLnpodWppY24yLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0yQ0ROIDIiLCJhZGQiOiIxODguMTE0Ljk5LjExIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xQ0ROIiwiYWRkIjoiMjAzLjMwLjE5MS4xOTIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjU2YTIxODhiLTJhYjctNDAyYy1iOWI4LTM0ODQ3ZmRmMDk1OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvNVFOUk9TUlYiLCJob3N0Ijoib3BsZzEuemh1amljbjIuY29tIiwidGxzIjoidGxzIn0=
    trojan://4331812b-92ff-47b5-9f32-78b5150e625f@t2.teslacdn1.live:443?allowInsecure=1#mianfeifq%20142
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzEyMjM1NjMiLCJhZGQiOiIxNjIuMTU5LjE0My4yMjIiLCJwb3J0IjoiMjA4MiIsInR5cGUiOiJub25lIiwiaWQiOiIzNmZhNDVkYi0yZDRhLTQyOTUtYTFmZS0yMjM4MzY5ODk4NzgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3BpbmVhcHBsZSIsImhvc3QiOiJQaW5lQXBwbGUuQ0xPVURGTEFSRS5RVUVTVCIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMENETiAyIiwiYWRkIjoiMTQxLjEwMS4xMTUuMzAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQwZDQ5NmE2LWNlZWItNDA5Ni1iYWViLTRjYzUyYjIwNTYyMSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRUNUQ0owREYiLCJob3N0IjoibGcxLnRydW1wMjAyMy51cyIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMUNETiIsImFkZCI6IjE0MS4xMDEuMTE0LjMwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6ImxnMS50cnVtcDIwMjMudXMiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzEyMjM1NTQiLCJhZGQiOiIxMDQuMTguMzcuMjE0IiwicG9ydCI6IjIwODIiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzZmYTQ1ZGItMmQ0YS00Mjk1LWExZmUtMjIzODM2OTg5ODc4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9waW5lYXBwbGUiLCJob3N0IjoiUGluZUFwcGxlLkNMT1VERkxBUkUuUVVFU1QiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xMkNETiIsImFkZCI6IjE5MC45My4yNDQuMyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2MS0xMkNETiAyIiwiYWRkIjoiMTkwLjkzLjI0NC4yIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0MGQ0OTZhNi1jZWViLTQwOTYtYmFlYi00Y2M1MmIyMDU2MjEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0VDVENKMERGIiwiaG9zdCI6ImxnMS50cnVtcDIwMjMudXMiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDIg5rOV5Zu9Q0ROMS0xMyIsImFkZCI6IjE5MC45My4yNDQuMjAwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0NjEyNjE4Yy0yNGNkLTQzNzktOTkyNC1jZmRmM2Q2MWZhNWEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0lZS0xENTNNIiwiaG9zdCI6Im9wZnIxLnYycmF5ZnJlZTEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDIg5rOV5Zu9Q0ROMS0xIiwiYWRkIjoiMTk4LjQxLjIxMi4xMjMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQ2MTI2MThjLTI0Y2QtNDM3OS05OTI0LWNmZGYzZDYxZmE1YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvSVlLTEQ1M00iLCJob3N0Ijoib3BmcjEudjJyYXlmcmVlMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzEyMjM1NjQiLCJhZGQiOiIxMDQuMTguODAuMjUxIiwicG9ydCI6IjIwODIiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzZmYTQ1ZGItMmQ0YS00Mjk1LWExZmUtMjIzODM2OTg5ODc4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9waW5lYXBwbGUiLCJob3N0IjoiUGluZUFwcGxlLkNMT1VERkxBUkUuUVVFU1QiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDIg5rOV5Zu9Q0ROMS0xNSIsImFkZCI6IjE5MC45My4yNDYuMTk1IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0NjEyNjE4Yy0yNGNkLTQzNzktOTkyNC1jZmRmM2Q2MWZhNWEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0lZS0xENTNNIiwiaG9zdCI6Im9wZnIxLnYycmF5ZnJlZTEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi02Q0ROIDIiLCJhZGQiOiIyMDMuMzAuMTg4LjE4OSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My03Q0ROIDIiLCJhZGQiOiIyMDMuMjQuMTA4LjEwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My0xM0NETiAyIiwiYWRkIjoiMTkwLjkzLjI0NC40IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    trojan://Huahua123@jp.huahua.company:443?allowInsecure=0#mianfeifq_12232022a119-147trojan
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.207.1.14:443#43.207.1.14443
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0zQ0ROIDIiLCJhZGQiOiIyMy4yMjcuMzguMzkiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjU2YTIxODhiLTJhYjctNDAyYy1iOWI4LTM0ODQ3ZmRmMDk1OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvNVFOUk9TUlYiLCJob3N0Ijoib3BsZzEuemh1amljbjIuY29tIiwidGxzIjoidGxzIn0=
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.206.226.94:443#43.206.226.94443
    

</details>

### 所有节点
合并节点总数: `2793`
[节点链接](https://raw.githubusercontent.com/baipiao250/HigeFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `81`
- [Alvin9999/pac2](https://github.com/Alvin9999/pac2), 节点数量: `82`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `152`
- [freefq/free](https://github.com/freefq/free), 节点数量: `37`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `8`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `138`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `176`
- [AzadNetCH/Clash](https://github.com/AzadNetCH/Clash), 节点数量: `465`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `63`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `5148`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `1`
- [云监控+[公益节点分享]](https://tz.fovi.tk), 节点数量: `12`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `45`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `52`
- [gfwglass 节点池](https://gfwglass.tk), 节点数量: `1`
- [Meteor-1337/Meteor](https://github.com/Meteor-1337/Meteor), 节点数量: `1`
- [hkaa0/permalink](https://github.com/hkaa0/permalink), 节点数量: `692`
- [ronghuaxueleng/get_v2](https://github.com/ronghuaxueleng/get_v2), 节点数量: `156`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `135`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `176`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `38`
- [mhmh1.top](https://mhmh1.top/art/50306.html), 节点数量: `20`
- [parkerpa/qw](https://github.com/parkerpa/qw), 节点数量: `45`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `5`
- [kxswa/k](https://github.com/kxswa/k), 节点数量: `38`
- [Nodefree.org](https://nodefree.org/f/freenode), 节点数量: `50`
- [Rokate/Proxy-Sub](https://github.com/Rokate/Proxy-Sub), 节点数量: `359`
- [mianfeifq/share](https://github.com/mianfeifq/share), 节点数量: `266`
- [peasoft/NoMoreWalls](https://github.com/peasoft/NoMoreWalls), 节点数量: `291`
- [ClashNode](https://clashnode.com/f/freenode), 节点数量: `50`

## 客户端选择
### 主流桌面客户端
|                            MacOS                             |                            Linux                             |                           Windows                            | 简易描述                                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------------------------------------------------- |
| [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW(Clash For Windows)](https://github.com/Fndroid/clash_for_windows_pkg/releases) | SS, SSR, Trojan, Vmess, VLESS协议支持，策略分流能力强。            |
|     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      | SS, SSR, Trojan, Vmess, VLESS, Trojan-Go协议支持（需安装相关插件）。 |
|                              ×                               |                              ×                               |      [V2rayN](https://github.com/2dust/v2rayN/releases)      | SS, Trojan, Vmess, VLESS协议支持，有测速，测延迟功能，支持订阅，二维码，剪贴板导入及手动配置。                 |
|                              ×                               |                              ×                               |    [WinXray](https://github.com/TheMRLL/winxray/releases)    | SS, SSR, Trojan, Vmess, VLESS协议支持，支持自动连接最快节点。            |
|                              ×                               |                              ×                               | [Shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows/releases) | SS协议支持， SS 专用客户端。                                       |
|                              ×                               |                              ×                               | [ShadowsocksR-windows](https://github.com/HMBSbige/ShadowsocksR-Windows/releases) | SSR协议支持，SSR 专用客户端。                                      |
|                [Surge](https://nssurge.com/)                 |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，著名网络调试工具，策略分流能力强大，需付费。                        |
|   [ClashX](https://github.com/yichengchen/clashX/releases)   |                              ×                               |                              ×                               | SS, SSR, Trojan, Vmess协议支持，占用资源较少。                   |
|      [V2rayU](https://github.com/yanue/V2rayU/releases)      |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，支持订阅，二维码，剪贴板导入，手动配置，二维码分享，与 V2RayN 类似。                        |

### 主流移动客户端
|                          iOS/iPadOS                          |                           Android                            | 简易描述                                                     |
| :----------------------------------------------------------: | :----------------------------------------------------------: | ------------------------------------------------------------ |
| [Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) | [Shadowrocket](https://play.google.com/store/apps/details?id=com.v2cross.proxy) | SS, SSR, Trojan, Vmess, VLESS协议支持，iOS端需在非国区 App Store 购买，美区售价 $2.99；安卓端非与 iOS 端同一作者，不支持 SSR 协议，免费且内置免费节点。 |
|                [Surge](https://nssurge.com/)                 |                              ×                               | SS, Trojan, Vmess协议支持，iOS 端著名网络调试工具，需付费。                                  |
| [Quantumult X](https://apps.apple.com/us/app/quantumult-x/id1443988620) |                              ×                               | SS, SSR, Trojan, Vmess协议支持，需在非国区AppStore购买，美区售价$4.99。 |
| [Potatso Lite](https://apps.apple.com/us/app/potatso-lite/id1239860606) |                              ×                               | SS, SSR协议支持，需在非国区AppStore购买，免费。              |
|                              ×                               | [Surfboard](https://play.google.com/store/apps/details?id=com.getsurfboard) | SS, SSR, Vmess协议支持，安卓端网络调试软件，兼容 Surge 2 配置。 |
|                              ×                               | [CFA(Clash For Android)](https://github.com/Kr328/ClashForAndroid/releases) | SS, SSR, Trojan, Vmess协议支持。                             |
|                              ×                               |  [SagerNet](https://github.com/SagerNet/SagerNet/releases)   | SS, SSR, Trojan, Vmess, VLESS协议支持。                      |
|                              ×                               | [Shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android/releases) | SS协议支持，安卓专用 SS 客户端。                                                 |
|                              ×                               | [ShadowsocksR-android](https://github.com/HMBSbige/ShadowsocksR-Android/releases) | SSR协议支持，安卓专用 SSR 客户端。                                                |
|                              ×                               |     [V2rayNG](https://github.com/2dust/v2rayNG/releases)     | SS, Trojan, Vmess, VLESS协议支持，v2ray 内核。                           |

## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

## 星标统计
[![Star History Chart](https://api.star-history.com/svg?repos=baipiao250/HigeFreeProxies&type=Date)](https://star-history.com/#baipiao250/HigeFreeProxies&Date)
