# randomName
随机生成中文姓名
###  功能
* 随机生成中文姓名，可以生成2位数的姓名例如：陈某，可以生成3位数的姓名例如：王某某，可以生成4位数的姓名例如：贺连某某
* 暂时没有收录少数名族的姓名
* 生成的姓名是utf-8编码格式
### 使用
        1. 若是python程序内使用，可以直接当作工具类来调用。

        2. 若是robotframework自动化测试使用：
            2.1. 将random_name.py复制到项目的根目录
            2.2. 在你的test suit中添加 Library random_name.py。
            2.3. 库加载成功后，搜索关键字查看是否加载成功
            2.4. 在你的test case中直接引用关键字
            2.5. 举个栗子：
            ${name}=	Get Name
            log	${name}



