# JupyterNotebookで表示する小数点以下の桁数を指定

%precision 3

3桁まで表示になる

pandasのDataFrameでは効かないので 違う方法で行う

pd.options.display.precision = 3
