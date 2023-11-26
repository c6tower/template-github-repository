# DEVELOPING TOOLS

## Branch Guidlines

|branch name|description|example|
|---|---|---|
|main||(none)|
|develop||(none)|
|release/yyyymmdd||release/20060102|
|feature/xxx_xxx|||
|hotfix/xxx_xxx|||


## Commit Message Guidlines

### Type

|prefix|description|
|---|---|
|feat|ユーザ影響のある仕様変更, 機能追加|
|fix|バグ修正, hotfix|
|improve|バグ修正や機能修正を伴わないコード改善, リファクタリング, 仕様変更を伴わないパフォーマンス改善, styleに分類されるフォーマット修正も含む|
|test|過不足のあるテストコードの追加・修正|
|docs|READMEやAPIDocsなどの追加・修正|
|chore|仕様の変更や機能修正を伴わない作業(ライブラリのバージョンアップ対応など), 開発補助ツールの整備(CI/CDの導入, ドキュメント生成ツールの追加・修正など)|

参考: https://github.com/angular/angular.js/blob/v1.8.3/DEVELOPERS.md#type
