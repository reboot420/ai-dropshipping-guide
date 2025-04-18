# AIデザイン活用型無在庫EC事業戦略ガイド

このリポジトリは、AI技術を活用したデザイン生成と無在庫販売方式を組み合わせた新規事業モデルのTypeScript Reactコンポーネントを提供します。TailwindCSSを使用したモダンなUIで、事業戦略の全体像をビジュアルに表現しています。

## 概要

このプロジェクトは、以下の要素で構成されています：

- 事業モデル全体フロー説明
- AIによるデザイン生成プロセスの説明
- 無在庫販売方式の事業優位性
- 自動化販売・物流システム構成
- 技術ソリューション比較分析（AIデザインプラットフォーム、商品モックアップ、製造パートナー）
- Shopify活用による初期コスト最適化
- コスト構造分析と収益性評価
- 段階的な事業展開ロードマップ

## 主な特徴

- **TypeScript**: 型安全で保守性の高いコード
- **ReactとTailwindCSS**: モダンなUIとレスポンシブデザイン
- **コンポーネント設計**: 再利用可能でモジュール化された構造
- **ビジュアル重視**: 図表やアイコンを使った分かりやすい表現

## インストール方法

```bash
# プロジェクトをクローン
git clone https://github.com/reboot420/ai-dropshipping-guide.git
cd ai-dropshipping-guide

# 依存パッケージをインストール
npm install

# 開発サーバーを起動
npm start
```

## 必要な依存関係

- React
- TypeScript
- lucide-react (アイコン)
- TailwindCSS (スタイリング)

## 使用方法

```tsx
import AIDropshippingGuide from './components/AIDropshippingGuide';

function App() {
  return (
    <div className="App">
      <AIDropshippingGuide />
    </div>
  );
}

export default App;
```

## カスタマイズ

コンポーネント内の各セクションは独立しており、TypeScriptの型定義により安全に内容やデザインを変更できます。TailwindCSSクラスを編集することで、デザインのカスタマイズが容易に行えます。

## ライセンス

MIT
