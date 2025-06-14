# CLIPモデルドキュメント

このドキュメントでは、CLIPモデルの使用方法と機能について説明します。

## 概要

このプロジェクトは、OpenAIのCLIPモデルを使用して画像と文章の関連性を学習・分析するための実装です。
主な機能は以下の通りです：

1. **ゼロショット画像分類**: 事前学習済みCLIPモデルを使用した画像分類
2. **CLIPモデルのファインチューニング**: 独自のデータセットでCLIPモデルをファインチューニング
3. **画像キャプション検索**: ファインチューニングしたモデルを使用して画像に最適なキャプションを検索
4. **画像生成プロンプト作成**: 画像から画像生成AIのためのプロンプトを作成

## インストール

```bash
pip install -r requirements.txt
```

## 使用方法

詳細な使用方法については、以下のセクションを参照してください：

- [ゼロショット分類](zero_shot.md)
- [ファインチューニング](finetuning.md)
- [キャプション検索](caption_search.md)
- [画像生成プロンプト](image_prompts.md) 