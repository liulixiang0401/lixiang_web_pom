#项目描述
这是web的自动化 项目，基于selenium+pytest


#环境准备


1.python 3.6
2.pytest  4.5.0

依赖包安装
> pip install -r requirements.txt

#运行用例

>pytest

#生成报告

生成allure报告

> pytest --alluredir ./allure_report

#pytest/ini配置的描述
'''
[pytest]

log_cli=0
;addopts=--alluredir ./allure_report
;testpaths = cases/module
;pyhon_files = test_*.py

user=yoyo
'''