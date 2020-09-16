# ログの送り方


1. Arkサーバーを起動するときにログを出力させる
    ark/Contaner/container-station-data/lib/docker/volumes/arkmanager.cfgをメモ帳(テキストエディタなら何でも)で開く
    arkflag_servergamelog=trueに変更する(24行目くらい)
    ファイル保存してサーバーを起動
2. 保存されているドライブ:/ark/serverShooterGame/Saved/Logs にServerGame.サーバー名.logが生成される → ログが保存される

---
ここまではサーバー管理者が設定

3. ログ解析のコードを実装
4. discord通知分を送信する

---
そっから先どうすればええんやろ．．．
