# BJTU_dissertation_latex_template_overleaf
- 北京交通大学LaTeX硕博学位论文（兼容Overleaf）工作流计划
- 一个[最近更新的BJTU本科毕设LaTeX模板](https://github.com/GhostCai/bjtu-thesis-dlc)

## Release
北京交通大学LaTeX硕博学位论文模板兼容Overleaf

> 在[https://github.com/yuweia/BJTU-thesis-templete](https://github.com/yuweia/BJTU-thesis-templete)的基础上修改\
经测试可以在Overleaf、Win(TeX Live)、macOS(MacTeX)环境下编译\

- [v1.0_overleaf兼容_Xe2024_BJTU学位论文双页模板_硕士学术学位_博士学术学位.zip](https://github.com/Bernard2050/BJTU_dissertation_latex_template_overleaf/blob/latest/release_history/v1.0/v1.0_overleaf%E5%85%BC%E5%AE%B9_Xe2024_BJTU%E5%AD%A6%E4%BD%8D%E8%AE%BA%E6%96%87%E5%8F%8C%E9%A1%B5%E6%A8%A1%E6%9D%BF_%E7%A1%95%E5%A3%AB%E5%AD%A6%E6%9C%AF%E5%AD%A6%E4%BD%8D_%E5%8D%9A%E5%A3%AB%E5%AD%A6%E6%9C%AF%E5%AD%A6%E4%BD%8D.zip)
    
    此版本中：
        · 修改了BJTU-thesis.cls和thesis.tex
        · 修复了封面到英文摘要的直接生成
        · 解决了多行公式（subequations）在前一页具有充足空间时可能会过早换页的问题

- v0.9 

    此版本中增加了对overleaf的兼容性(XeLaTex, Tex Live 2024)

## 目标
- 工作流: vscode + TeX Live (LaTeX编译环境) + LaTeX-Workshop (vscode插件) + Overleaf (在线环境) + github (仓库/项目版本管理) + zotero (文献管理)

- 项目文档：sphinx项目文档、使用说明

## Overleaf下的使用

· 进入project后打开左上角menu，compiler选择XeLaTex, Tex Live 2024，
· main document选择demo.tex\
· 注意overleaf官方部署免费版编译速度可能过慢，并提示compile time out

## 本地编译器安装使用

- 下载链接

| 项目 | Visual Studio Code | TeX Live | Git | Zotero |
|------------|------------|------------|------------|------------|
| **链接**    | [Win/Mac/Linux](https://code.visualstudio.com/download)  | [Win/Mac/Linux](https://tug.org/texlive)   | [Win/Mac/Linux](https://git-scm.com/downloads) | [Win/Mac/Linux](https://www.zotero.org) |

- Win下TeX Live安装注意

> TeX Live的Win Gui在线安装方式(install-tl-windows.exe)下载缓慢，建议直接下载完整的ISO：\
[BJTU镜像](https://mirror.bjtu.edu.cn/CTAN/systems/texlive/Images/texlive2024-20240312.iso)|[PKU镜像](https://mirrors.pku.edu.cn/ctan/systems/texlive/Images/texlive2024-20240312.iso)\
加载texliveyyyy-yyyymmdd.iso后运行install-tl-windows.bat进入Gui安装界面；\
选择安装目录避免中文，并且TEMP目录不能出现中文。


