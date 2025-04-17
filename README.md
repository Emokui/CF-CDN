## CF镜像任何网站


## 环境变量

| 变量名                    | 必填  | 默认值   | 示例                                             | 备注                  |
|------------------------|-----|-------|------------------------------------------------|---------------------|
| PROXY_HOSTNAME         | √   |       | github.com                                     | 代理地址 hostname       |
| PROXY_PROTOCOL         | ×   | https | https                                          | 代理地址协议              |
| PATHNAME_REGEX         | ×   |       | ^/username/                                  | 代理地址路径正则表达式         |
| UA_WHITELIST_REGEX     | ×   |       | (curl)                                         | User-Agent 白名单正则表达式 |
| UA_BLACKLIST_REGEX     | ×   |       | (curl)                                         | User-Agent 黑名单正则表达式 |
| IP_WHITELIST_REGEX     | ×   |       | (192.168.0.1)                                  | IP 白名单正则表达式         |
| IP_BLACKLIST_REGEX     | ×   |       | (192.168.0.1)                                  | IP 黑名单正则表达式         |
| REGION_WHITELIST_REGEX | ×   |       | (JP)                                           | 地区白名单正则表达式          |
| REGION_BLACKLIST_REGEX | ×   |       | (JP)                                           | 地区黑名单正则表达式          |
| URL302                 | ×   |       | https://github.com/Emokui/Sukuna | 302 跳转地址            |
| DEBUG                  | ×   | false | false                                          | 开启调试                |
