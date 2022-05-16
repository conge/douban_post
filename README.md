# douban_post
抓取指定ID在豆瓣指定小组内的发言。
由于豆瓣ID不是唯一的，所以可能会重复


本程序使用了第三方库
	requests
	BeautifulSoup
	lxml

可以使用pip来安装：
	pip install requests bs4 lxml

## 只在一个组内查找

```bash
python single_group.py
```

### 查找用户在其加入的所有组的发言

```bash
python douban_post.py
```
输入用户名：conge
输入密码：xxxx
不需要验证码。 'NoneType' object has no attribute 'attrs'
登录成功！
输入用户ID：conge
输入组链接：https://www.douban.com/group/runners/discussion?start=0
该小组共有...页
你想查找多少页？默认查找全部100
正在查找第1页
发现帖子：
                       以跑半马为目标，应该练距离即可，用165心率跑步还...
