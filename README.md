lilAssetGrimoire
====

# This project is under development and may be subject to breaking changes
# このプロジェクトは開発中であり破壊的な変更がされる場合があります

## 説明

これは[GUIDのデータベース](https://github.com/lilxyzw/guid_database)を見てプロジェクトに不足しているツールやシェーダーを特定するツールです。不足しているアセットがデータベースに登録されている場合、エラーになっているマテリアルやコンポーネントのInspectorに不足アセットが表示されます。データベースは`Tools/lilAssetGrimoire/Update Database`で更新できます。

## データベースにないツールを登録する手順

1. `Tools/lilAssetGrimoire/Make Target (*)`でデータベースに登録するターゲットを選択
  - `Make Target (Folder)`はProjectウィンドウで選択中のフォルダをターゲットとして指定します
  - `Make Target (Unitypackage)`はプロジェクト外のunitypackageを直接ターゲットとして指定します
2. `Assets/GUIDList/`内に手順1で指定したターゲットの設定が追加されるので必要に応じて設定を編集
3. `Tools/lilAssetGrimoire/Output GUIDs`をクリックし、ダイアログでデータベース出力先フォルダを選択
4. [guid_database](https://github.com/lilxyzw/guid_database)のPull Requestで追加リクエストを送信
