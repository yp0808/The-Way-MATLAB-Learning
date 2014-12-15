# MATLAB学习笔记  
作者：[HereChen](http://herechen.github.io/about/)

目前尚处于编辑中，不是完整版。  
此项目旨在将我之 MATLAB 所学总结一遍，并在总结中 “温故而知新”。  
这里存档的是文档源码，用 LaTeX 语言排版，使用 TexLive 包，以 XeLaTex 方式编译。

## 文件说明

0. MATLABTips.tex -- 主文件
1. abstract.tex -- 摘要
2. secJustStart.tex -- 学途伊始
3. secFeaturesSome.tex -- 一些功能
4. secFunctionsSome.tex -- 一些函数
5. secSkillsSome.tex -- 一些技巧
6. secEfficientCoding.tex -- 高效编程
7. secSpiceHere.tex -- 额外兴趣
8. appendix.tex -- 附录
9. format.cls -- 宏包和格式设置文件
10. title.cls -- 封面设置
11. mcode.sty -- MATLAB 代码列出包
12. MATLABTips.pdf -- 生成的PDF文档

## MATALB Tips 更新记录

1. 开始更新记录日期：2014-01-01
2. 此文档开始编辑日期：2013 夏
3. 后期改进备注：
添加网页登陆方面知识、MATLAB的类学习、函数依赖检查 Dependency Report

- 最后更新：2014/12/15 16:59:40
- 2014/12/2 22:27:51 格式更改
- 2014-05-14 10:41:27 添加Command窗口格式显示设置内容
- 2014-04-21 23:01:43 添加工作目录设置以及直接通过路径文件设置路径的方法
- 23:09 2014/3/22 将标题移至摘要文件，并删除个人配置信息
- 23:09 2014/3/22 目录改为双排
- 23:09 2014/3/22 在学途伊始中加入一个实例――牛顿法求根
- 23:45 2014/3/19 添加一节内容：学途伊始，并对其他地方作了修改
- 11:18 2014/3/12 小幅修改Function一节 
- 0:56 2014/3/6 图片问题继续解决：图片画布设置为统一宽度18cm，显示宽度为 0.8\textwidth，段落的 0.8 倍宽度.
- 0:56 2014/3/6 解决代码间距设置，引起边框问题，于是改之
- 0:56 2014/3/6 修改一些细节
- 0:56 2014/3/6 删除我的MATLAB界面内容

#### 11:19 2014/3/4

1. 添加页眉页脚设置
2. 重新定义itemize
3. 重新设置页面
4. 去除 notation 灰色背景，并设置楷体
5. 重新设置行间距为 1.3
6. 对函数和兴趣两节小幅修改，作内容和格式上的调节

改进方向  
1. 表格源码当作为源文件引入
2. 代码行间距设置


#### 0:03 2014/3/4

1. 删除各章节专用文件夹、新建图表专用文件夹、并直接设置图形路径（不必添加路径）
2. 所有格式用专用文件保存
3. 总结起来，再次精简了源文件结构
4. 对高效编程一节小幅修改

改进方向  
1. 表格源码当作为源文件引入
2. noation当以其他字体展现，去除灰色背景
3. 代码行间距设置


#### 13:23 2014/3/3

1. 补充保护代码一节
2. 添加公式、图片打印内容
3. 代码框改为但边框，简洁
4. 一些细节改善
5. 我的MATLAB界面图片放到appendix文件夹中,并删除image目录


#### 11:31 2014/3/2

1. 补充代码发布一节
2. 修正代码列出与文字间距离过大
3. note项添加灰色背景
4. 代码列出添加可定义的关键词及其颜色设置
5. 小幅修改代码保护和错误警告两节

改进方向  
1. 我的MATLAB界面图片放到appendix文件夹中,并删除image目录


#### 13:47 2014/3/1

1. 补充断点调试一节
2. 解决图片同比例压缩问题
3. 路径设置添加图片
4. 我的MATLAB界面调到附录


#### 16:17 2014/2/28

1. 添加note
2. 添加附录
3. 改善代码列出
4. 调整章节结构
5. 调正内容，明确各章节内容
6. 每个章节以单独文件存储，优化Latex文档结构
7. 优化Latex源码注释格式
8. 编写内容

改进方向    
1. 代码作为文件引用
2. 内容


#### 1:26 2014/2/28

1. 主要优化代码列出
2. 代码可在目录中列出
3. 添加图片
4. 删减部分冗余内容


#### 19:04 2014/1/1

1. 解决代码列出段前距离过长，使用\vspace{-5mm}
2. 开始文档更新记录
3. 增加常用函数章节
4. 添加警告和错误、删除单元执行快捷方式一节（重复）
5. 自定义函数使用 help 一节的修改
6. MATLAB 启动方式

改进方向    
1. 代码列表在目录中显示
2. 代码并列