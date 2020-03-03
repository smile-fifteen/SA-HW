### library
- *.designer.cs为ui设计
- *.cs为对应designer的bll
- library.cs为与数据库连接的dal
- ui和bll耦合度较高,难以复用

### jdbc02
- ui文件夹下为ui模拟,调用bll
- biz文件夹下为封装好dal的bll
- dao文件夹下是与数据库连接和基本语句封装的dal
- bean是数据的基本结构定义
- 分层详细明确,对于同样的结构可以重复使用
