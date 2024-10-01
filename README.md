# BJTU_dissertation_latex_template_overleaf
北京交通大学LaTex学位论文模板（兼容Overleaf）开发计划

## 目标
- 工作流: vscode + TeX Live (LaTex编译环境) + LaTex-Workshop (vscode插件) + Overleaf (在线环境) + github (仓库/项目版本管理) + zotero (文献管理)

- 项目文档：sphinx项目文档、使用说明

## 安装使用

- 下载链接

| 项目 | Visual Studio Code | TeX Live | Git | Zotero |
|------------|------------|------------|------------|------------|
| **链接**    | [Win/Mac/Linux](https://code.visualstudio.com/download)  | [Win/Mac/Linux](https://tug.org/texlive)   | [Win/Mac/Linux](https://git-scm.com/downloads) | [Win/Mac/Linux](https://www.zotero.org) |

- Win下TeX Live安装注意

> TeX Live的Win Gui在线安装方式(install-tl-windows.exe)下载缓慢，建议直接下载完整的ISO：\
[BJTU镜像](https://mirror.bjtu.edu.cn/CTAN/systems/texlive/Images/texlive2024-20240312.iso)|[PKU镜像](https://mirrors.pku.edu.cn/ctan/systems/texlive/Images/texlive2024-20240312.iso)\
加载texliveyyyy-yyyymmdd.iso后运行install-tl-windows.bat进入Gui安装界面；\
选择安装目录避免中文，并且TEMP目录不能出现中文。

- Overleaf下的使用

· 进入project后打开左上角menu，compiler选择XeLaTex，main document选择demo.tex\
· 免费版编译速度可能过慢，并提示compile time out
