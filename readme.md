# 《Flask Web开发》前六章的代码

### Run...

创建虚拟环境`virtualenv env`

激活虚拟环境`source env/bin/activate`

安装需要的库`pip install -r requirements.txt`

迁移数据库`python hello.py db migrate`

### Good parts
- 坚持使用虚拟环境
    + virtualenv env
    + source env/bin/activate
    + deactivate
- 熟悉Git
    + git clone
    + git pull
    + git fetch
    + git merge
    + git push
    + git branch
    + git checkout
- 采用装饰器实现理由控制`@app.route('/', method=['GET', 'POST'])`
- 上下文全局变量
    + current_app 程序上下文
    + g           程序上下文
    + request     请求上下文
    + session     请求上下文
- 使用Jinja2模板引擎
- 优雅的Flash消息
- 采用关系型数据库sqlite
- Flask 扩展
    + flask-script
    + flask-bootstrap
    + flask-moment
    + flask-wtf
    + flask-SQLAlchemy
    + flask-migrate
