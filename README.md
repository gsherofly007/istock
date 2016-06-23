# istock
istock 是一个抓取沪深股市的行情，并按照个人的喜好进行分析和整理的项目。集成了数据抓取、量化分析、以及制定相关的选股测略等相关的模块。深度分析股票涨跌的相关因素，找到一个合理的风险控制策略，保证稳定的盈利状态。但是股市的行情是会变化的，并不能保证一定会盈利。

## 技术依赖

建议使用 Python3.3+ 的版本，PostgreSQL 9.2 以上的数据库。

### 配置项目

- 取下项目代码

```shell
$ git clone https://github.com/itpubs/istock.git
```

- 环境配置,在项目根目录下执行如下命令

```shell
$ pyenv venv
$ source venv/bin/activate
```

- 安装第三方的依赖模块

```shell
$ pip install -r requirements.txt
```

- 初始化项目

```shell
$ ./run.py --init
```

请确保已经安装 PostgreSQL 数据库，并处于运行状态。如果没有数据库，也可以使用部分功能，不过无法持久化数据，无法对数据进行持续分析。以 *nix 系统为例：


