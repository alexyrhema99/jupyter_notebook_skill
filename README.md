# jupyter_notebook_skill
Record some useful(?) jupyter notebook skill.
> Last change 20190315

*   [一些jupyter notebook小技巧](#一些jupyter notebook小技巧)
*   [Running MRO kernel on jupyter](#Running MRO kernel on jupyter)
    *   [running CARN R](##running CARN R)
    *   [running Microsoft R Open, MRO](##running Microsoft R Open, MRO)

**Keywords: jupyter notebook skill, encoding **

---
# 一些jupyter notebook小技巧
> 目錄、快速鍵、結果隱藏、theme設定等等

- [原文_28 Jupyter Notebook tips, tricks, and shortcuts](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/)
- [【精心解讀】關於Jupyter Notebook的28個技巧](https://zhuanlan.zhihu.com/p/32600329)
- [[譯]27 個Jupyter Notebook的小提示與技巧](http://liuchengxu.org/pelican-blog/jupyter-notebook-tips.html)

- [Jupyter notebook extensions](https://github.com/ipython-contrib/jupyter_contrib_nbextensions)
    - 官方Github，有安裝教學
- [python -- Jupyter Notebook 添加目錄索引、更換主題、解決工具欄隱藏問題](https://blog.csdn.net/August1226/article/details/80762632)
- [jupyterlab-toc](https://github.com/jupyterlab/jupyterlab-toc)
    - 官方Github，有安裝教學
    - 但是我目前安裝失敗，因為要先安裝 nodels 的樣子。(20190314)
        > Errored, use --debug for full output:
ValueError: Please install nodejs 5+ and npm before continuing installation. nodejs may be installed using conda or directly from the nodejs website.

- [jupyterthemes](https://github.com/dunovank/jupyter-themes)
    - 官方Github，有安裝與使用設定教學
- [jupyterthemes](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/toc2/README.html)
    - 官方Github，有安裝與使用設定教學。(介面看起來比較friendly~XD)



---
# Running MRO kernel on jupyter

## running CARN R
如果想安裝一般的R到jupyter上面，就去官方的IRkernel看
他有一個github.io網站比較好瀏覽
另外也可以透過Anaconda做安裝，Aanaconda有官方說明
- https://github.com/IRkernel/IRkernel
- https://irkernel.github.io/
- https://docs.anaconda.com/anaconda/user-guide/tasks/use-r-language/

## running Microsoft R Open, MRO
如果想安裝MRO在jupyter上面運行，可以看下面的連結，與後續追蹤
但是我目前不確定我是不是有安裝成功，我覺得是有啦!!
- https://jev-pankov.com/2017/09/22/jupyter-notebook-r-kernel-for-microsoft-r-open/
- https://github.com/IRkernel/IRkernel/issues/574
- https://stackoverflow.com/questions/44056164/jupyter-client-has-to-be-installed-but-jupyter-kernelspec-version-exited-wit



