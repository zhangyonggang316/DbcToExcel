# DbcToExcel
DBC 文件和Excel文件相互转换；需要安装在matlab app中运行.
Tips：用的是matlab2022b把包的app，2022b以后的版本可以直接运行；之前的请下载源码自行打包；
# 下载&安装
去到仓库主分支main下载所有的文件，把.zi文件解压之后，Dbc2Excel.mlappinstall文件直接拖到matlab的命令窗口，点击确认即可安装成功！
![Image_20240226170104](https://github.com/zhangyonggang316/DbcToExcel/assets/81631716/9b9b7d14-402b-42ac-bd3b-033892a406d5)

![Image_20240226172155](https://github.com/zhangyonggang316/DbcToExcel/assets/81631716/d6acc0fc-1403-424a-889e-4174850669f9)

![Image_20240226172340](https://github.com/zhangyonggang316/DbcToExcel/assets/81631716/181bcbda-b351-448d-bc7f-58bffb29ab72)
## 使用说明
# 生成Excel模板
点击 Dbc2Excel APP 打开app；
点击dbc2excel选项卡，点击“导出Excel模板”，即可在当前文件夹生成一个标准的can J1939解析文件；

![PixPin_2024-02-26_17-30-40](https://github.com/zhangyonggang316/DbcToExcel/assets/81631716/0d83660c-7a75-45b2-873c-02f10eef03ac)
![PixPin_2024-02-26_17-34-44](https://github.com/zhangyonggang316/DbcToExcel/assets/81631716/a1b14fbf-4480-4d47-9d4e-5fee05fe5df0)

# Excel 转 DBC
在excel2dbc选项卡下，点击“文件选择“”，选择刚才生成的Excel，然后再点击“生成DBC”，即可生成对应的DBC文件；

![PixPin_2024-02-26_17-40-09](https://github.com/zhangyonggang316/DbcToExcel/assets/81631716/c857082b-1cc3-4891-bb14-7b314915f95c)

# DBC 转Excel
在dbc2excel选项卡下，点击“文件选择“”，选择刚才生成的dbc，然后再点击“生成Excel”，即可生成对应的Excel文件；

![PixPin_2024-02-26_17-41-52](https://github.com/zhangyonggang316/DbcToExcel/assets/81631716/fec0b882-c0a2-4468-985d-bcdd975221a9)
![Image_20240226174345](https://github.com/zhangyonggang316/DbcToExcel/assets/81631716/419be8eb-22dd-418f-8a16-d5dbcbfbbc9e)


# 其它功能
其它选项功能：
DBC名称：可以改写生成的DBC名字；
sheetm名：加载Excel后显示所有的表单，通过选择“单独生成”，“集合生成”DBC文件；
项目编号：节点通道：设置生成Excel的名字；
