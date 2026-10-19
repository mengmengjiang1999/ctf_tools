# ctf_tools —— CTF 工具集归档

个人 CTF 工具集的 GitHub 备份。原位置：`~/Tools/`。

## 工具清单

| 目录 | 说明 |
|---|---|
| Docker准备/ | qiling、Doughnuts 等 PLC/仿真相关环境（原 .git 已剥离） |
| [WIN]CTF工具合集/ | Windows CTF 工具合集（取证工具与推荐书籍，超大书籍未入库） |
| misc-tools/ | 杂项小工具 |
| web_scan/ | sqlmap、dirsearch、dirmap、Tentacle、fscan 等 web 扫描工具（上游 clone，已剥离 .git） |
| pwndbg/ pwntools/ | pwn 调试/开发框架 |
| binwalk/ upx/ volatility3/ CyberChef/ | 逆向/取证/解包常用 |
| x64dbg/ stegsolve/ ctf-tools/ Poseidon/ IDAGolangHelper/ | 调试器/隐写/自动化脚本集 |

## 未入库说明

- burpsuite pro（503M 商业 jar）、xray_*（商业授权二进制）：请从官方渠道获取
- jeb/（858M 商业反编译器）：未入库
- 单文件 >100MB：GitHub 拒收
- 命令行工具（binwalk 等 brew 包）见 Brewfile

## 恢复

git clone git@github.com:mengmengjiang1999/ctf_tools.git
brew bundle --file=Brewfile
