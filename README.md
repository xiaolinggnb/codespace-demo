# command input in GitHub CodeSpace without using dev-contianer

```shell
# 创建虚拟环境
@xiaolinggnb ➜ /workspaces/python-dev-container-demo (master) $ python -m venv .env
# 激活并进入虚拟环境
@xiaolinggnb ➜ /workspaces/python-dev-container-demo (master) $ source .env/bin/activate
# 安装依赖
(.env) @xiaolinggnb ➜ /workspaces/python-dev-container-demo (master) $ pip install -r requirements.txt 
# 尝试运行项目
(.env) @xiaolinggnb ➜ /workspaces/python-dev-container-demo (master) $ flask --app hello run
