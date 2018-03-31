# CI_template
【勉強用】CIの各処理用テンプレート

YAML系のCIツールで実現予定

## 内容
- ビルド
- デプロイ
- テスト
    - MT
    - CT
    - ST

## テスト
- テストスイート
    - 前処理
        - ディレクトリ構成作成
        - データ生成
        - 環境変数設定
    - テストケース群実行
    - 後処理
        - ディレクトリ構成削除
        - データ削除
        - 環境変数設定
- テストケース
    - 前処理
        - ディレクトリ構成作成
        - データ生成
        - 環境変数設定
        - 性能採取開始
    - テストケース実行
    - 後処理
        - ディレクトリ構成削除
        - データ削除
        - 環境変数設定
        - 性能採取終了
        - 成否判定
        - 生産物保存
 
 - テスト要因は要因と因子の一覧テンプレートを用意しておき、一覧の中から利用するものや組み合わせを設計、新規開発などで不足すれば追加とし、要因一覧とテスト項目一覧は独立して管理できるようにしておきたい。
 
