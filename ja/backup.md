---
layout: page
title: バックアップと復元
---

{% include nav-ja.md %}

# バックアップと復元

## バックアップを書き出し

1. 設定 > **ローカルバックアップ** を開く
2. **バックアップを書き出し** をタップ
3. `.deskaier` ファイルとして保存（壁紙を含む）

## 復元

1. 設定 > **ローカルバックアップ** > **バックアップを復元**
2. `.deskaier / .zip / .json` を選択
3. 復元完了後に **今すぐ再起動** で反映

## 復元時のポイント

- 端末内保存だけでなく、クラウド保存ファイルからの復元も可能
- 大きいファイル（壁紙同梱など）でも復元できるよう最適化済み
- 壊れたファイルは `Unsupported or broken backup file` と表示

## どんな時に使う？

- 端末移行時
- レイアウトを大きく変更する前の保険
- Work / Personal 構成の退避

## 動画（MP4）

#### バックアップ/復元導線（設定画面）
バックアップ書き出し・復元メニューへ到達するまでの操作です。
<video controls playsinline preload="metadata" style="max-width: 100%; border-radius: 10px;">
  <source src="./assets/pro/backup-restore-flow.mp4" type="video/mp4">
</video>

## 復元後チェックリスト（推奨）

1. アプリを再起動したか確認
2. ホーム表示（ウィジェット / AIクイック起動 / ピン留め）を確認
3. Pro利用時は、AIクイック起動優先順や自動モード切替ルールも確認
4. 必要なら最新状態で再度バックアップを作成

関連:
- [ホーム画面と表示設定](./settings)
- [Pro機能チュートリアル](./pro-features)
