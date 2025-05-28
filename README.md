# UniDok

**UniDok（ユニドック）** は、UnityEditor を一切使わずに Unity プロジェクトやアセットファイル（Scene、Prefab、Meta、Settings など）を自動生成するための .NET ライブラリ兼 CLI ツールです。

## 特徴

- UnityEditor に依存しない完全なファイル操作
- CLI を通じたバッチ生成・スクリプト化の自動化
- .unity / .meta / ProjectSettings 含む多様なアセットフォーマットに対応予定
- DDDベースのクリーンな設計で再利用・拡張が容易

## 使用技術

- .NET 8.0 / C#
- CLI（System.CommandLine または Spectre.Console）
- YAMLパーサ（YamlDotNet など）
- JSON設定ファイル対応

## ライセンス

MIT License
