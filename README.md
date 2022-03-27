# Shopping_memo
![スクリーンショット_2022_03_28_001610_border](https://user-images.githubusercontent.com/65009243/160288346-f53c6d2b-7370-4cc3-bd92-614c29f2a000.png)

Firebase Realtime Database、JavaScriptを使って、買い物時に使えるメモアプリを作成しました

アクセスURL：https://shopping-memo-c551e.web.app/

## アプリ使用説明
上部テキストボックスに品名を入力し「追加」ボタンを押下することで買い物リストに品物が反映されます

![image](https://user-images.githubusercontent.com/65009243/160288898-7880e9e1-d9be-42a7-b92d-cb10eaf4dc45.png)

チェックボックスにチェックをいれ「入手完了」ボタンを押下することで入手済みリストへ品物が移動できます

![image](https://user-images.githubusercontent.com/65009243/160288756-05f5f252-69fc-4e10-a32d-84f750235fb6.png)

不要になった項目はチェックボックスにチェックをいれ「削除」ボタンを押すことで品物を削除できます

![image](https://user-images.githubusercontent.com/65009243/160288839-1e4bfe9d-c299-4982-916c-55bd7dc5a4ba.png)

## バグ・課題点
・同じ品物を追加しようとすると追加が行えなかったりバグが発生してしまう(画面を更新することである程度は解消可能)

・複数ウィンドウで使用すると品物が複数個追加されてしまう(画面を更新することで正しい値を表示することが可能)


## 使用技術
・HTML、CSS

・JavaScript

・Firebase Realtime Database



