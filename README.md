# Dots-and-Boxes
[![PyPI version](https://img.shields.io/pypi/v/DotsAndBoxes.svg)](https://pypi.python.org/pypi/DotsAndBoxes)

点格棋

本软件是一个点格棋博弈软件，可用于人人对战，人机对战和机机对战功能。
用户运行软件后，要先通过“工具-设置红方/蓝方玩家”，来添加红方和蓝方玩家（后期可通过此处加载AI），之后从“文件-新游戏”创建游戏，左侧是棋盘，右侧分别显示当前玩家、当前步数、得分和历史信息，通过双击历史信息，可以跳转到特定步。在跳转到某一步后，如果不更改落子，则历史信息不会变化，如果用户更改落子位置，则历史信息被删除并添加新的落子位置。用户可以随时保存游戏，在游戏没有开始或者结束后可以加载之前保存的游戏。

软件具有载入和导出大学生计算机博弈大赛点格棋标准棋谱文件

程序使用py3实现点格棋对弈基础功能，并使用pyqt5构建了人机交互界面。

安装方法
pip install DotsAndBoxes

运行环境要求：
Python3

UI界面适配
Windows 10
Ubuntu Desktop 1604
