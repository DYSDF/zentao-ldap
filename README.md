## 禅道开源版LDAP插件

支持从LDAP服务器上同步用户信息（账号、真实姓名、邮箱），以及使用LDAP验证登录。

### 简介
  1. 插件安装后，在后台页面会多出一个"LDAP"子页面，可在该页面配置LDAP服务器信息
  2. 在LDAP配置页面可以测试是否能够正常连接LDAP服务器
  3. 保存配置后，点击“手动同步”按钮，从LDAP服务器上同步用户信息
  4. 同步用户信息以后，可以使用LDAP用户登录禅道
  5. 未同步的账户会在首次使用ldap账户登录后自动创建本地账户
  5. 本地用户，通过在账户名称前加“$”符号来登录禅道

### 安装
  1. 通过禅道的插件管理来进行安装。
      1. 使用管理员身份登录禅道，访问插件管理。
      2. 打开获得插件页面，搜索找到本插件。
      3. 选择自动安装，按照页面提示即可。
  2. 手工安装，将代码解压缩，然后将目录拷贝到禅道对应的目录，比如module拷贝到zentao的module。