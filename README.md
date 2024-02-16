# 日記＋感情分析アプリ

## 概要

普段の日記から日記のポジティブ・ネガティブ傾向を分析し、良し悪しの情報を閲覧できるシステム

## ユースケース

- 感情分析機能
- より良い行動プラン・アクションを提示する機能
- メンタルの可視化・共有機能
- マッチング機能？

### URL

- デプロイ？：https://kadoblog.pythonanywhere.com/
- MeCab：`POST` https://kadoblog.pythonanywhere.com/api/mood-check
  - body: {text:"形態素解析・感情分析したいテキスト"}
