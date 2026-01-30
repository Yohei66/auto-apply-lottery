## 以下のコマンドで仮想環境アクティベート
``` myenv\Scripts\activate ```

## 以下コマンドで、Pythonファイルを実行
 ``` py tennis_book.py ```

## 以下インストール
``` pip install pandas openpyxl jpholiday selenium webdriver_manager ```


# EXE化手順
## PyInstaller 用の venv を有効化
```pyinstallervenv\Scripts\activate```-

## selenium と webdriver-manager を最新版にする
```pip install -U selenium webdriver-manager```

## exe を作成
```pyinstaller --onefile --noconsole --clean --name kasukou_auto_apply_lottery --add-data "kasukou_auto_apply_lottery.xlsx;." kasukou_auto_apply_lottery.py```
  ```

## distフォルダ配下にEXEファイルが追加されます。
