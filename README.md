# Personnel-Records

```mermaid
graph TD
a[用户User] --- u{拥有}
u{拥有} --- b[日记Daily]
u{拥有} --- c[笔记Notes]
u{拥有} --- d[日程Schedule]
u{拥有} --- e[读书Read]
u{拥有} --- f[个人信息PersonalInformation]
u{拥有} --- z[账单]
g((日期)) --- b[日记]
h((内容)) --- b[日记]
c[笔记] --- i((日期Date))
c[笔记] --- j((内容Content))
d[日程] --- l((日期Date))
d[日程] --- m((地点address))
d[日程] --- n((目的Purpose))
e[读书] --- o((时间Date))
e[读书] --- p((书名Title))
e[读书] --- r((作者author))
e[读书] --- s((感悟Thought))
z[账单] --- zz((时间date))
z[账单] --- za((金额money))
z[账单] --- zb((备注note))
t((手机号PhoneNumber)) --- f[个人信息]
v((昵称Nickname)) --- f[个人信息]
w((邮箱Emalil)) --- f[个人信息]
x((座右铭Motto)) --- f[个人信息]


```

### 注册 



## 流程

```mermaid
graph LR
A[注册] ==> B[日记]
B[日记] ==> C[笔记]
C[笔记] ==> D[账单]
D[账单] ==> E[日程]
E[日程] ==> F[读书]
```
## SQL 存储过程
### 用户部分
- [x] 用户注册 
- [x] 用户更改密码
- [x] 登陆
### 日记部分
- [x] 日记添加
- [x] 日记查询
- [ ] 日记修改
- [ ] 日记删除
### 笔记部分
- [ ] 笔记添加
- [ ] 笔记查询
- [ ] 笔记修改
- [ ] 笔记删除
### 账单部分
- [ ] 账单添加
- [ ] 账单查询
- [ ] 账单修改
- [ ] 账单删除
- [ ] 账单总和
- [ ] 账单月总和
### 日程部分
- [ ] 日程添加
- [ ] 日程查询
- [ ] 日程修改
- [ ] 日程删除
### 读书部分
- [ ] 读书添加
- [ ] 读书修改
- [ ] 读书查询
- [ ] 读书删除


### 综合部分
- [ ] 时间线数据返回
- [ ] 综合搜索
- [ ] 用户登陆查询
- [ ] 用户登陆后展示对应信息

## 后端

- [ ]将数据生成JSON 

## 页面
### 类似于teambition界面样式侧边栏(左侧) 用户时间线(右侧)
使用jquery UI组建库
- [ ] 登陆
- [ ] 注册
- [ ] 修改密码
- [ ] 用户主界面(设置为已经添加的日程)
- [ ] 时间线