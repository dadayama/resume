## 基本情報

- 名前：山田 かおり
- [GitHub](https://github.com/dadayama)

## スキルセット

- HTML/CSS
- JavaScript (React / Next.js / Astro)
- アクセシビリティチェック

## 職務経歴

### 株式会社ノベルティ (2024 年 1 月 〜 現在)

#### 担当業務

- Next.jsや Astro を用いたサイト制作
- アクセシビリティに配慮した実装・改善
- 設計、デザイン、実装段階でのアクセシビリティチェック
- 既存サイトの保守運用(WordPress)

#### 担当案件

- [株式会社ストレージ王 サービスサイト](https://www.storageoh.jp/)
- [株式会社ジェイシーサプライ 施工業者のマッチングアプリ](https://skettable.com/)

#### 主な実績

##### 実装
- React Hooks を活用した状態管理・コンポーネント設計
- React Hook Form + Zod / Yup によるフォームバリデーション実装
- REST API / microCMS を利用した記事管理・動的コンテンツ実装
- 検索機能の構築、Google Maps API による地図表示機能の開発
- アクセシビリティを考慮したセマンティックなマークアップ、WAI-ARIA の使用

##### アクセシビリティチェック・改善（一例）

###### 設計時
- 見出し要素に関連する情報の配置ルールを確認し、見出しの前に関連情報を配置しないよう提案  [1.3.1 情報及び関係性](https://waic.jp/translations/WCAG22/#info-and-relationships)
- リンクテキストと遷移先ページタイトルの不一致を指摘し、改善を提案 [2.4.4 リンクの目的 (コンテキスト内)](https://waic.jp/translations/WCAG22/#link-purpose-in-context) [2.4.9 リンクの目的 (リンクのみ)](https://waic.jp/translations/WCAG22/#link-purpose-link-only)
- 各ナビゲーションの構成の不一致を指摘し、情報設計の改善を提案 [3.2.3 一貫したナビゲーション](https://waic.jp/translations/WCAG22/#consistent-navigation)
- フォームパーツに適切な説明文を設置するよう提案、説明文の位置をフォームパーツの上に設置するよう提案 [3.3.2 ラベル又は説明](https://waic.jp/translations/WCAG22/#labels-or-instructions)
- ユーザーの操作が必要な UI コンポーネント（ポップアップ、モーダル、アコーディオンなど）を極力減らすよう提案

###### デザイン時
- DOMの順序を考慮したレスポンシブデザインの調整を提案 [1.3.2 意味のあるシーケンス](https://waic.jp/translations/WCAG22/#meaningful-sequence)
- 形だけで表されている要素に対し、可視テキストの追加を提案 [1.3.3 感覚的な特徴](https://waic.jp/translations/WCAG22/#sensory-characteristics)
- コラムカテゴリ部分のコントラスト比不足箇所のカラー調整をデザイナーに依頼 [1.4.3 コントラスト (最低限)](https://waic.jp/translations/WCAG22/#contrast-minimum)
- 自動再生コンテンツについて、5秒以上連続して動くものには一時停止・再生ボタンの設置を提案 [2.2.2 一時停止、停止、非表示](https://waic.jp/translations/WCAG22/#pause-stop-hide)
- SNSアイコンのみのリンクに対し、可視テキストの追加を指示 [2.4.6 見出し及びラベル](https://waic.jp/translations/WCAG22/#headings-and-labels)

###### 実装時
- img要素のalt属性に設定されているテキストと画像の内容の不一致を指摘 [1.1.1 非テキストコンテンツ](https://waic.jp/translations/WCAG22/#non-text-content)
- 見出しの前に見出しに関連する要素がある場合は、hgroup要素を使用しグルーピングするよう提案  [1.3.1 情報及び関係性](https://waic.jp/translations/WCAG22/#info-and-relationships)
- `button` 要素のアクセシビリティネーム（可視テキストと `aria-label`）の不一致を修正依頼 [1.3.1 情報及び関係性](https://waic.jp/translations/WCAG22/#info-and-relationships) [4.1.2 名前 (name)・役割 (role)・値 (value)](https://waic.jp/translations/WCAG22/#name-role-value)
- 検索フォームの `input` と `label` の正しい紐づけを実施  [1.3.1 情報及び関係性](https://waic.jp/translations/WCAG22/#info-and-relationships) [2.4.6 見出し及びラベル](https://waic.jp/translations/WCAG22/#headings-and-labels)
- `h1`〜`h6`要素の使用箇所・レベルの適切な調整を実施  [2.4.6 見出し及びラベル](https://waic.jp/translations/WCAG22/#headings-and-labels) [2.4.10 セクション見出し](https://waic.jp/translations/WCAG22/#section-headings) [2.4.1 ブロックスキップ](https://waic.jp/translations/WCAG22/#bypass-blocks)
- サイドメニューのフォーカス順序の調整と、モーダル時のフォーカストラップ実装を依頼 [2.1.2 キーボードトラップなし](https://waic.jp/translations/WCAG22/#no-keyboard-trap) [2.4.3 フォーカス順序](https://waic.jp/translations/WCAG22/#focus-order)
- 英語タイトルのテキストに対して `lang="en"`を設定するよう依頼 [3.1.2 一部分の言語](https://waic.jp/translations/WCAG22/#language-of-parts)

##### その他
- 社内コーディングガイドライン、アクセシビリティガイドラインの策定と運用

### 株式会社東京商工リサーチ (2019 年 10 月 〜 2023 年 7 月)

#### 担当業務

- 財務データの集計、入力
- チーム全体の進捗管理
- 業務担当者の割当、各業務のマニュアル作成
- 来客対応

### 福祉相談職 (2015 年 4 月 〜 2018 年 3 月)

#### 担当業務

- 介護施設、小学校での相談支援員
- 施設入居者のケア
- 施設入居希望者のヒアリング
- 関連施設との連携
- 地域、家庭訪問
- リハビリテーション会議への参加
