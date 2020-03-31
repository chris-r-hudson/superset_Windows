# Install Apache Superset on Windows 
A easy way to install [Apache Superset](https://github.com/apache/incubator-superset) on Windows

1. first of all, you should install [miniconda](https://docs.conda.io/en/latest/miniconda.html) or [anaconda](https://www.anaconda.com/distribution/)
2. Download superset.yml, then modify name and prefix to what you want.
3. run the command 

```
conda env create -f superset.yml
```
4. Apache superset initialization 

for detail steps please visit,
* [Install Apache Superset on Windows 10 Without Admin Rights(English)](http://lab.alitrack.com/blog/install-apache-superset-on-windows-10-without-admin-rights/)
* [Windows 10 下快速安装Apache Superset(Chinese)](http://lab.alitrack.com/blog/windows-10-%e4%b8%8b%e5%bf%ab%e9%80%9f%e5%ae%89%e8%a3%85apache-superset/)


P.S.

superset.yml got with the following command,

```
source activate superset
conda env export > superset.yml
```
