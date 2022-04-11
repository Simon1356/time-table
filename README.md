# Simon 工具箱时刻表管理系统

## ① 关于

Simon 工具箱时刻表管理系统是由 B 站 Up 主 Simon1356 创建的专门为小程序“Simon 工具箱”生成和管理时刻表模块的工具，系统可以导入/导出或手动新建列车时刻表，导出的 JSON 配置文件可用于 Simon 工具箱数据库，并显示成易读的时刻表。
https://Simon1356.github.io/time-table

注意：此项目目前有两个版本，分别在两个分支上

- main 分支 为旧版本 1.0，此版本生成合读取的文件仅供 2022 年 4 月 7 日之前版本的小程序读取
- new 分支 为新的 2.0 版本，此版本对于整体的逻辑进行了较大的调整，数据格式也有所变动，新版小程序已于 2022 年 4 月 7 日上线，仅可读取新版本的结构。

## ② 使用方法

### 一：导入 or 新增

- 选择导入文件或直接新建

### 二：基本信息

- 线路名称
- 列表中的位置，即在小程序时刻表页面中顶部的位置，从 0 开始数
- 滚动消息，即在小程序页面中顶部滚动的“时刻表更新于”后面的文字内容

### 三：车站

- 点击添加/编辑车站
- 车站名称以空格分隔

### 四：时刻表

- 点击添加车次
- 填好对应的信息以及标识（全程/临时/支线/各停）
- 如需修改则点击对应行的修改按钮即可

### 五：导出

- 按一下“导出”按钮

### 六：关于

- 巴拉巴拉介绍

## ③ 示例

详见示例**EXAMPLE**文件夹

# Simon ToolBox Management System

## ① About

Simon ToolBox Management System is a web application that was created specifically for its WeChat mini-program "Simon ToolBox". The system can import/export and create timetables for trains. A JSON file can be exported to serve the database of Simon ToolBox which can be then transformed into a readable timetable.

Notice: This project contains two versions located in two different branches.

- Branch main, version 1.0 of the project. This version serves only the WeChat mini-program published before April 7th, 2022.
- Branch new, version 2.0 of the project. This version has changed a lot in its procedures and data structures. Therefore, it can be used only for the newly published version of WeChat mini-program.

## ② Instructions

Change the language with the up-right selector on the page.

### 1: Import or Export

- Click the button on the page.

### 2: Basic information

- Line name
- Position in list. The position of line name on the top of the mini-program page. Count starts from 0.
- Top notification. Literal meaning

### 3: Stations

- Click add/edit station
- Station names should be separated by SPACE.

### 4: Timetable

- Click "Add Train"
- Fill up all information.
- Click Edit button to edit one train.

### 5: Export

- Click "Export"

### 6:About

- Introduction blabla

## ③ 示例

Examples are in **EXAMPLE** folder.
