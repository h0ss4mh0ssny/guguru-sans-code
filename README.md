https://github.com/h0ss4mh0ssny/guguru-sans-code/releases

# Guguru Sans Code: Hybrid Dev Font (Google Sans Code + IBM Plex JP)

[![Releases](https://img.shields.io/badge/releases-downloads-brightgreen?logo=github&logoColor=white)](https://github.com/h0ss4mh0ssny/guguru-sans-code/releases)

Guguru Sans Code is a programming font designed to be comfortable for developers who write in both Latin and Japanese scripts. It blends the precision of Google Sans Code for Latin glyphs with the clarity of IBM Plex Sans JP for Japanese glyphs. The result is a single, cohesive monospaced font family that aims to reduce eye strain and improve readability across multilingual codebases.

レンチミッションの要点
- 開発者が日英両方の環境で一貫した見た目を保てるように設計されたプログラミングフォントです。
- 西洋文字に Google Sans Code の設計を、和文には IBM Plex Sans JP の設計を組み合わせています。
- コードを長時間読む作業でも読みやすさと統一感を提供することを目指しています。

Table of Contents
- Overview
- Why Guguru Sans Code
- Design Philosophy
- Features
- Font Formats and Compatibility
- System Requirements
- Getting Started
- Installation Instructions
- Quick Start Examples
- Typography and Accessibility
- Performance and Rendering Tips
- Cross-Platform Considerations
- Customization and Theming
- Contributing
- Release Notes and Licensing
- FAQ
- Community and Support
- Roadmap

Overview
Guguru Sans Codeは、ソフトウェア開発者の作業に最適化されたフォントです。コードの可読性を高めるために、字形間の均一性と文字間のバランスを重視しています。Latin文字と日本語の文字セットの両方が、同じデザインチームのビジョンで統一感をもって描かれています。視線の移動を最小限に抑え、キーボード入力の波及効果を軽減することを狙いとしています。

Why Guguru Sans Code
- 多言語コードの一貫性: 日本語と英数字の混在コードでも、字形の揃いが崩れにくい設計です。
- 読みやすさを最適化: 文字の太さ、間隔、組み方を最適化して長時間のコーディングでも疲れを軽減します。
- 互換性と拡張性: ベースとなるフォントはウェブとデスクトップの両方で使えるフォーマットを想定しており、様々な環境で快適に使えます。
- デザインの一貫性: Google Sans Code の現代的な美学と IBM Plex Sans JP の正確さを組み合わせ、一貫したビジュアルを提供します。
- コミュニティとエコシステム: フォントに関わる環境（エディタ、IDE、テーマ、カラー）と自然に馴染むように設計されています。

Design Philosophy
- 一貫性を最優先: Latin と Japanese の字形が互いを邪魔しないよう、同じ比率とリニアな感覚を保ちます。
- 可読性重視: プログラミング特有の記号列や識別子、キーワードが識別しやすいように設計しています。
- 実務適用性: IDE、エディタ、ターミナル、ウェブアプリのフォントとして現場で使えることを想定しています。
- アクセシビリティ: コントラストと形状のエンフォースに配慮し、視認性の高いデザインを目指します。

Features
- バイリンガルサポート: 英語と日本語を同時に扱うコードファイルでの見え方を最適化。
- 等幅設計: コードブロック、識別子、関数名、変数名が整然と揃います。
- ウェブフォント対応: WOFF/WOFF2 形式でウェブプロジェクトにも容易に組み込み可能。
- デスクトップ対応: TTF/OTF 形式で Windows、macOS、Linux での使用が想定されています。
- 多様なウェイト: light, regular, medium, bold など、幅広いウェイトを提供。ハイライトやエディタの強調表示に対応。
- 文字セットの充実: ASCII 文字だけでなく、基本的な日本語全体をカバー。記号や数学記号のレンダリングにも注意を払っています。
- 凝った字形の整合性: 類似文字が混同されないよう、見分けやすさを念頭に置いたデザインを採用。

Font Formats and Compatibility
- Latin and Kana scripts 共存を前提としたフォントファミリ。以下のファイル形式を含めることを想定しています。
  - TrueType Font (TTF)
  - OpenType Font (OTF)
  - Web Font (WOFF/WOFF2)
- 互換性の高いオプションを提供しており、古い IDE から新しいエディタまで幅広く利用可能です。
- ファイルは Releases ページに配置されています。最新リリースには Latin + Japanese の全フォーマットが同梱されます。

System Requirements
- 最新のオペレーティングシステム: Windows, macOS, Linux のいずれかを想定。
- フォントファイルをインストールする権限。
- ウェブ用途ならモダンブラウザ（Chrome、Edge、Firefox、Safari など）で WOFF/WOFF2 のサポートが前提。
- テキストエディタや IDE の設定で font-family に "Guguru Sans Code" を指定できる環境。

Getting Started
このセクションは、フォントを日常の開発作業に取り入れるための第一歩を示します。導入はシンプルで、フォントファイルをプロジェクトのフォントディレクトリやローカルのフォント場所に置くだけです。以降のガイドは、実務での運用を前提にしています。

Downloading and Installing from Releases
- 配布ファイルは以下のリリースページに格納されています。https://github.com/h0ss4mh0ssny/guguru-sans-code/releases
- このリンクには実際のフォントファイルが含まれています。ファイルをダウンロードして、各環境の手順に沿ってインストールします。
- インストール後はフォント名を「Guguru Sans Code」に設定して、エディタのプレビューや既存の設定を確認します。

Quick Start
- ウェブプロジェクトでの導入
  - CSS で @font-face を使い、Guguru Sans Code を優先フォントとして指定します。
  - フォールバックとして sans-serif 系を設定します。
- デスクトップ環境での導入
  - 各OSのフォント管理ツールから font ファイルを追加して、アプリケーションでの選択肢に現れたら選択します。

Example: CSS for Web Usage
- 以下のコードは単一ファイルのプロジェクトの例です。
- まずフォントファイルをプロジェクトの assets/fonts ディレクトリに配置します。
- その後、以下の設定を CSS に追加します。

@font-face {
  font-family: 'Guguru Sans Code';
  src: url('/assets/fonts/GuguruSansCode-Regular.ttf') format('truetype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: 'Guguru Sans Code';
  src: url('/assets/fonts/GuguruSansCode-Medium.ttf') format('truetype');
  font-weight: 500;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: 'Guguru Sans Code';
  src: url('/assets/fonts/GuguruSansCode-Bold.ttf') format('truetype');
  font-weight: 700;
  font-style: normal;
  font-display: swap;
}

body {
  font-family: 'Guguru Sans Code', ui-sans-serif, system-ui, -apple-system;
}

Code blocks and inline code can use the same font family for visual consistency.

Typography Examples
- This section demonstrates how the type behaves in a real-world code sample.
- It includes a sample of JavaScript, HTML, and CSS snippets to show alignment, spacing, and readability.

Code Snippet Example
function greet(name) {
  const message = `Hello, ${name}!`;
  console.log(message);
  return message.length;
}

const user = { name: 'Guguru', role: 'Code Enthusiast' };
console.log(user.name);

HTML Example
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <title>Guguru Sans Code Preview</title>
  <style>
    @font-face {
      font-family: 'Guguru Sans Code';
      src: url('/font/GuguruSansCode-Regular.ttf') format('truetype');
      font-weight: 400;
      font-style: normal;
      font-display: swap;
    }
    body { font-family: 'Guguru Sans Code', system-ui, sans-serif; }
  </style>
</head>
<body>
  <h1>サンプル見出し</h1>
  <p>この段落は Guguru Sans Code のウェブ版で表示される見た目を示しています。</p>
</body>
</html>

Japanese-Only Viewing
- 日本語の読みやすさを重視し、日本語 glyph の配置と形状を最適化しています。
- コードで日本語コメントが使われる場合でも、識別子のレンダリングが崩れにくいよう工夫しています。
- 日本語と英数字が混在する長い行も、適切な改行と間隔で読みやすさを保つよう設計されています。

Accessibility and Readability
- コントラストとフォントサイズの調整が容易で、視覚的な疲労を減らします。
- 柔らかい曲線と直線のバランスを取り、識別の速さを改善します。
- 調整可能なウェイトと字形の組み合わせにより、見出しやコードブロックの階層を明確にします。

Performance and Rendering Tips
- ウェブページでの最適化
  - font-display: swap を活用して、フォントが読み込まれる前でもテキストが表示されます。
  - WOFF2 形式を優先して読み込むと、ファイルサイズが小さく、描画が速くなります。
- デスクトップアプリケーションでの最適化
  - フォントサブセットの作成を検討して、使用するグリフだけをロードするオプションを検討します。
  - DPI 設定に応じてフォントサイズを調整することで、表示の均一性を保てます。

Cross-Platform Considerations
- Windows
  - フォントファイルを右クリックしてインストールします。複数のウェイトがある場合は、各ファイルを個別に追加します。
- macOS
  - フォントファイルをダブルクリックして Font Book でインストールします。フォントの検証と同期を行い、全アプリで利用可能にします。
- Linux
  - ユーザーのフォントディレクトリにコピーします。fc-cache -f -v を実行してキャッシュを更新します。
  - 多くのデスクトップ環境でフォントの管理が GUI で可能です。適切なディレクトリ配分を選択します。

Customization and Theming
- カラーとテーマの組み合わせ
  - ダークモードとライトモードの両方で読みやすさを確保します。
  - ハイコントラスト用の追加ウェイトや glyph の調整を将来のリリースで検討します。
- フォントの派生
  - 日本語の一部 glyph を微調整した派生ファミリを検討することも可能です。コミュニティのフィードバックを受けて改善を続けます。
- 変種ファミリ
  - イタリック体や太字の派生を追加して、コードスタイルの表現力を広げる検討を進めています。

Contributing
- 貢献の方法
  - テキストファイルのフォント名やコードサンプルの整合性を保つため、フォントファイルの変更は Releases ページのワークフローに沿ってください。
  - バグ報告・提案は Issues で行い、詳細な再現手順と環境情報を添えてください。
  - ドキュメントの追加・改善は README の更新、Markdown のセマンティックな構造の提案、サンプルコードの追加などを含みます。
- コードのスタイル
  - 一貫性を保つため、エディタ設定ファイルや CSS サンプルの共有時は同じフォーマットを使用します。
- テストと検証
  - 多言語環境でのレンダリングをテストします。異なるOSとブラウザでの表示を確認します。

Release Notes and Licensing
- Releases ページにはフォントファイルとライセンス情報が含まれます。
- 本フォントファミリの著作権とライセンスは、リリースにて明示的に提供されます。ライセンス条項は releases のパッケージ内文書を参照してください。
- 公式リリースには、フォーマット別のファイル名、対応プラットフォーム、ウェイトの配分、対応スクリプトの一覧が記載されています。
- ライセンスに関する質問はリリースノートのセクションで確認してください。

FAQ
- なぜこのフォントを作ったのですか？
  - 開発者が日本語と英語のコードを同じフォントで読みやすく書く環境を作りたかったからです。文字の均一性と読みやすさを重視しました。
- どのような環境で最適ですか？
  - IDE、テキストエディタ、ターミナル、ウェブアプリなど、コードを書くすべての環境で使えるよう設計しています。
- どのファイルを使えばいいですか？
  - あなたの環境に合ったファイル形式を選択してください。ウェブでは WOFF2、デスクトップには TTF/OTF を推奨します。
- 日本語と英語を混在させたコードで問題はありますか？
  - 文字間のバランスと形状を統一するよう設計しており、混在した場合でも読みやすさを保てるのが利点です。

Examples and Gallery
- プリビューページやスクリーンショットを活用して、フォントの見え方を視覚的に示します。以下は代表的なサンプルです。
- コードブロックの rendered 例、エディタの UI、ターミナルの表示などのキャプチャを適宜挿入します。著作権のある素材は使用条件を遵守してください。

Gallery and Previews
- 例1: コードビューの見た目
  - 画像をここに挿入（実際のスクリーンショットを適宜配置）
- 例2: 日本語と英語の混在テキスト
  - 画像をここに挿入
- 例3: ダークテーマでの表示
  - 画像をここに挿入

Images and Assets
- 本リポジトリには、フォントファイルそのものを含める場合と、リリースで配布される場合があります。正確なファイルは Releases ページを参照してください。リンクを繰り返し示すことで、ユーザーがすぐにダウンロード先へアクセスできるよう配慮しています。

Releases and How to Access Them Again
- 本リポジトリの最新のフォント資材は Releases ページに集約されています。リンクの再案内を以下の点で行います。
- ダウンロード先の再案内
  - 最新リリースは、リリースページに格納されています。https://github.com/h0ss4mh0ssny/guguru-sans-code/releases
  - このリンクにはファイルが含まれており、取得後にインストールを行います。ファイルはプラットフォームごとに分かれている場合があります。

Usage Scenarios
- IDE の新しいフォントとしての適用
  - 人気のある IDE のフォント設定を開き、Guguru Sans Code を選択します。エディタの色設定と組み合わせて、ハイライトの可読性を最大化します。
- ブラウザベースの開発
  - ウェブフォントとして読み込む場合、適切なスタイルシートを用いて font-family を指定します。
- ドキュメント作成
  - 日本語と英語の混在文章を執筆する際にも、統一感のある文字形で表現できます。

Developer Experience
- 本フォントは、開発者が日常のワークフローに取り込みやすいよう、導入の手間を減らすことを優先しています。
- 直感的なファイル命名と表現、分かりやすいデモンストレーションを用意しています。
- ドキュメントとサンプルコードが、実務での適用をすばやく進められるよう設計されています。

Roadmap
- 2025年内のリリース計画
  - さらなるウェイトとベースラインの追加
  - より広いプラットフォーム対応
  - ウェブフォントのサブセット化オプション
- 2026年以降の展望
  - 変種ファミリの拡張
  - 国際化の改善
  - コントラストとダークモードの最適化

Support
- 質問や問題がある場合は Issues をご利用ください。
- 具体的な環境情報（OS、エディタ、フォントファイルのバージョン、使用したファイル形式）を添えてください。
- 公式の連絡先情報はリリースノートと README のライセンスセクションに記載しています。

Endnotes
- 本 README は、日本語と英語の併記を中心に、実務での活用を想定した長期的なガイドとして作成されています。
- ユーザーのご意見を反映して、フォントの改善と新機能の追加を継続します。
- 初期のリリースから長期的なサポートと改善を提供することを目指しています。

Releases and Licensing Deep Dive
- Releases ページの各資材には、フォントファイルのフォーマット別の対応表と、推奨のインストール手順が含まれます。最新情報は常に releases ページをご確認ください。
- ライセンス条項は Release パッケージ内のライセンス文書を参照してください。フォントの再配布、改変、商用利用の条件は、それらの文書で定義されています。
- 著作権表示とクレジットの取り扱いについても、リリースノートとライセンスファイルに従ってください。

Release Download Guidance
- ダウンロードは Releases ページに格納されたファイルを直接取得します。該当ファイルをダウンロードしてから、上記の各プラットフォームの手順に沿ってインストールします。
- ファイル構成はリリースごとに異なる場合があります。複数ファイルが含まれている場合は、プラットフォームに適したものを選びます。
- フォントを正しく反映させるには、インストール後にアプリケーションを再起動してください。場合によってはフォントキャッシュの再生成が必要です。

Final Notes
- Guguru Sans Code は、開発者のニーズを満たすために設計されたフォントセットです。多言語コードの描画を最適化し、日常的なコーディング作業を快適にします。
- ご利用の環境に合わせて、フォントファイルの形式や設定を適切に選択してください。
- ここに示したガイドは、実務の現場での活用を想定して作成されています。適切な導入と運用で、コードの可読性と作業生産性を向上させることを目指します。