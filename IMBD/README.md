IMBD 2021 ^^ Command Line
------
```Bash
# 列出權重loss最小的前15個檔案
ls | sort -n -t- -k4 | head -n 15
```
```Bash
# 強制刪除資料夾/檔案
rm -r weight/
rm -r xxx.py
```
```Bash
# 複製檔案至有編輯權限的路徑
# (EX：~根目錄具有編輯權限)
cp xxx.py ~
```
```Bash
# 進入已建置好的虛擬環境
pipenv shell
```
```Bash
# GPU資源查詢
nvidia-smi
```
```Bash
# 列出所有項目(包含隱藏文件夾及檔案)
ls -al
```
