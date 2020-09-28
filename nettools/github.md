<!--
 * @Author: Donnyyan
 * @Date: 2020-09-28 18:01:53
 * @LastEditTime: 2020-09-29 08:29:53
 * @LastEditors: Donnyyan
 * @FilePath: \Tools\nettools\github.md
-->
# github 访问常见问题


## dns 被污染

将以下配置写入 host 文件

```markdown

192.30.253.112 github.com 
192.30.253.119 gist.github.com
151.101.184.133 assets-cdn.github.com
151.101.184.133 raw.githubusercontent.com
151.101.184.133 gist.githubusercontent.com
151.101.184.133 cloud.githubusercontent.com
151.101.184.133 camo.githubusercontent.com
151.101.184.133 avatars0.githubusercontent.com
151.101.184.133 avatars1.githubusercontent.com
151.101.184.133 avatars2.githubusercontent.com
151.101.184.133 avatars3.githubusercontent.com
151.101.184.133 avatars4.githubusercontent.com
151.101.184.133 avatars5.githubusercontent.com
151.101.184.133 avatars6.githubusercontent.com
151.101.184.133 avatars7.githubusercontent.com
151.101.184.133 avatars8.githubusercontent.com

```

或将以下配置写入代理的 pac 设置中

```makrdown
github.com,
gist.github.com,
assets-cdn.github.com,
raw.githubusercontent.com,
gist.githubusercontent.com,
cloud.githubusercontent.com,
camo.githubusercontent.com,
avatars0.githubusercontent.com,
avatars1.githubusercontent.com,
avatars2.githubusercontent.com,
avatars3.githubusercontent.com,
avatars4.githubusercontent.com,
avatars5.githubusercontent.com,
avatars6.githubusercontent.com,
avatars7.githubusercontent.com,
avatars8.githubusercontent.com,
```