# systrace环境

- 下载链接：[Python2.7.18](https://www.python.org/downloads/release/python-2718/)

- Python环境变量(安装python时勾选底部环境变量配置可略去这一步)
  - 新建PYTHON_HOME，值：python安装主目录路径
  - Path添加值：%PYTHON_HOME% 和 %PYTHON_HOME%/Scripts

- 安装组件（进入Scripts目录执行：`cd python/Scripts`）
  - `[python -m] pip install --upgrade pip` （更新pip，非必须）
  - `pip install pypiwin32` （安装win32con组件）
  - `pip install six` （安装six组件）
  - `pip uninstall <pakagename>` （卸载组件使用）