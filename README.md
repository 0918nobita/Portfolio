# Portfolio

[![Twitter @0918nobita](https://img.shields.io/badge/Twitter-%400918nobita-blue.svg?style=flat-square&logo=twitter)](https://twitter.com/0918nobita) [![Scrapbox 0918nobita](https://img.shields.io/badge/Scrapbox-0918nobita-3CAC86?style=flat-square)](https://scrapbox.io/0918nobita/) [![Qiita 0918nobita](https://img.shields.io/badge/Qiita-0918nobita-brightgreen.svg?style=flat-square)](https://qiita.com/0918nobita)

松本 幸大  
2000/02/16 生 (現在 19 歳)

## 概要

- 滋賀県在住
- リモート or 京都オフィスにて、TypeScript と Haskell を用いた Web アプリの開発案件を担当
- プログラミング言語そのものに興味があり、日々技術書やネット上の記事を参考に勉強を進めている
  - 型システム・ラムダ計算・意味論
  - 関数型プログラミング
    - F#, OCaml, Haskell, Elm
  - その他のプログラミング言語
    - Idris (依存型), FORTH (低レイヤ・メタプログラミング)
  - 言語処理系
    - 自作プログラミング言語のインタプリタ・コンパイラの開発
- Web アプリ開発
  - Babel, Webpack, Parcel 等のビルド環境の利用
  - Angular + NgRx
  - React(TS) + Redux (+ redux-thunk | redux-saga) + Hooks
  - Vue.js(ES or TS) + Vuex
  - Firebase Cloud Functions / Firestore を用いたサーバーレス Web アプリ
  - WebAssembly
- 「作りたいものに見合った技術選定をする」ことを重要視している
  - 日々の勉強には、その技術選定の際の自分の引き出しを増やす目的もある
  - 機能要件のための技術選定か、開発者の体験向上のための技術選定かを区別して考えている

## 制作物

- (執筆作業中) **技術同人誌「F# ではじめる パーサコンビネータ」**
  - F# を用いて、実際に様々なパーサ / パーサコンビネータを実装しながら周辺の理論や技術を学べる同人誌
  - 継続、モナド、ビルダークラス、コンピュテーション式などについて言及する
  - [第二回技術書同人誌博覧会](https://gishohaku.dev/)・[技術書典 8](https://techbookfest.org/event/tbf08) で頒布予定
- **FORTH 言語入門書「DARK FORTH - Prologue」** [BOOTH](https://t.co/P311mCRU0U)
  - A5 サイズ, 64 ページの技術同人誌
  - [技術書典 7](https://techbookfest.org/event/tbf07) で頒布した ([サークル詳細ページ](https://techbookfest.org/event/tbf07/circle/5638538418716672))
- (開発中) **自作プログラミング言語「Psyche」** [リポジトリ](https://github.com/0918nobita/psyche)
  - WASM を出力する軽量言語のコンパイラ
  - 当初は OCaml で開発し OPAM でリリースしていたが、<br>現在は F# に移植して開発を進めている ([OPAM パッケージ詳細ページ](https://opam.ocaml.org/packages/psyche/))
- (開発中) **プログレッシブ Web アプリ「Tsundoku」** [リポジトリ](https://github.com/0918nobita/Tsundoku)
  - (新バージョン) React v16 + @ionic/react v4
    - [Undux](https://undux.org/) でフロントエンドの状態管理
  - (旧バージョン) Angular v6 + [Ionic](https://ionicframework.com/) v3
    - [NgRx](https://ngrx.io/) でフロントエンドの状態管理
    - [Firebase Authentication](https://firebase.google.com/docs/auth/?hl=ja) でユーザー管理
    - [Cloud Functions](https://firebase.google.com/docs/functions/?hl=ja) でサーバーサイドスクリプトを実装
    - [Cloud Firestore](https://firebase.google.com/docs/firestore/?hl=ja) (セーブデータを保存)
    - [Netlify](https://www.netlify.com/) Hosting (CD)
- **Hello World in Rust (without libc)** [リポジトリ](https://github.com/0918nobita/low-level-helloworld)
  - libc に依存せず、直接連携する手書きアセンブリプログラム (x86_64) から<br>システムコールを発生させて Hello World するプログラムを作成した
- **自作プログラミング言語「Xemime」** [リポジトリ](https://github.com/xemime-lang/xemime)
  - Kotlin + Java + Gradle (開発初期は Java + Maven)
  - Xemime: JavaScript に影響を受けたプロトタイプベースオブジェクト指向言語
  - プログラミングコンテスト「あいちゃれ」(後述) に応募して最優秀賞を獲得
- **Web アプリ「英単語プレテスト」** [リポジトリ](https://github.com/0918nobita/eitango_pretest)
  - PHP + SQLite
  - レンタルサーバ上にアップロードして公開
- **活動記録管理システム** [リポジトリ](https://github.com/0918nobita/Activity-Recording-System)
  - C# + WPF
  - 初めて開発したウィンドウアプリケーション


## 今読んでいる技術書

- [3D グラフィックス API Vulkan を出来るだけやさしく解説する本](https://fadis.booth.pm/items/1562222)
- [Clean Architecture - 達人に学ぶソフトウェアの構造と設計](https://www.amazon.co.jp/Clean-Architecture-%E9%81%94%E4%BA%BA%E3%81%AB%E5%AD%A6%E3%81%B6%E3%82%BD%E3%83%95%E3%83%88%E3%82%A6%E3%82%A7%E3%82%A2%E3%81%AE%E6%A7%8B%E9%80%A0%E3%81%A8%E8%A8%AD%E8%A8%88-Robert-C-Martin/dp/4048930656/ref=sr_1_1?ie=UTF8&qid=1548211522&sr=8-1&keywords=clean+architecture)
- [プログラミング言語の基礎概念](https://www.amazon.co.jp/%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0%E8%A8%80%E8%AA%9E%E3%81%AE%E5%9F%BA%E7%A4%8E%E6%A6%82%E5%BF%B5-%E3%83%A9%E3%82%A4%E3%83%96%E3%83%A9%E3%83%AA%E6%83%85%E5%A0%B1%E5%AD%A6%E3%82%B3%E3%82%A2%E3%83%BB%E3%83%86%E3%82%AD%E3%82%B9%E3%83%88-%E4%BA%94%E5%8D%81%E5%B5%90-%E6%B7%B3/dp/4781912850/ref=sr_1_1?s=books&ie=UTF8&qid=1548211698&sr=1-1&keywords=%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0%E8%A8%80%E8%AA%9E%E3%81%AE%E5%9F%BA%E7%A4%8E%E6%A6%82%E5%BF%B5)
- [プログラム意味論](https://www.amazon.co.jp/%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%A0%E6%84%8F%E5%91%B3%E8%AB%96-%E6%83%85%E5%A0%B1%E6%95%B0%E5%AD%A6%E8%AC%9B%E5%BA%A7-%E6%A8%AA%E5%86%85-%E5%AF%9B%E6%96%87/dp/4320026578)
- [コンパイラの構成と最適化](https://www.amazon.co.jp/%E3%82%B3%E3%83%B3%E3%83%91%E3%82%A4%E3%83%A9%E3%81%AE%E6%A7%8B%E6%88%90%E3%81%A8%E6%9C%80%E9%81%A9%E5%8C%96-%E4%B8%AD%E7%94%B0-%E8%82%B2%E7%94%B7/dp/4254121776/ref=sr_1_3?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&keywords=%E3%82%B3%E3%83%B3%E3%83%91%E3%82%A4%E3%83%A9%E3%81%AE%E6%A7%8B%E6%88%90%E3%81%A8&qid=1561218844&s=books&sr=1-3)
- [型システム入門 - プログラミング言語と型の理論](https://www.amazon.co.jp/%E5%9E%8B%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%85%A5%E9%96%80-%E2%88%92%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0%E8%A8%80%E8%AA%9E%E3%81%A8%E5%9E%8B%E3%81%AE%E7%90%86%E8%AB%96%E2%88%92-Benjamin-C-Pierce/dp/4274069117/ref=sr_1_cc_1?s=aps&ie=UTF8&qid=1548211658&sr=1-1-catcorr&keywords=%E5%9E%8B%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%85%A5%E9%96%80)

## 活動内容

### ブログ

はてなブログ「名残」 https://0918nobita.hateblo.jp

### OSS

- npm パッケージの開発
  - [wasm-ts](https://github.com/0918nobita/wasm-ts) : WebAssembly API に対する TS 型定義を提供する
  - [customizable-gitmoji-cli](https://github.com/SnO2WMaN/customizable-gitmoji-cli)
- Vue.js 公式ドキュメントの翻訳
- MDN の JavaScript リファレンスの翻訳 ([プロフィール](https://developer.mozilla.org/ja/profiles/0918nobita))

### コミュニティ

- FORTH 言語に関する情報を共有したり、プログラマ同士で交流するためのコミュニティ「forth-jp」の立ち上げ・運営

### イベント

- [FRONTEND CONFERENCE 2019](https://2019.kfug.jp/) (会場スタッフとして参加)
- [LINE Developer Meetup](https://line.connpass.com/)
  - 登壇して PWA についての LT を行った ([発表資料](https://speakerdeck.com/0918nobita/firebasewoshi-tutezuo-rupwa-line-developer-meetup-number-43))
- [ng-kyoto Angular Meetup](http://ng-kyoto.github.io/)
- [技術書典](https://techbookfest.org/)
- [プランクトンサミット](https://plankton-summit.github.io/)

## 経歴

- (2019/10/01 〜) [HERP, Inc.](https://herp.co.jp/) にエンジニアインターン生として参加
- (2019/09/04 ～ 09/13) ピクシブ株式会社 サービス開発インターンシップ 2019 夏<br>「SUMMER BOOT CAMP 2019」に参加して、[pixivFACTORY](https://factory.pixiv.net/) の実際の開発に携わった
- (2019/02/21 〜 03/29) 株式会社サイバーエージェント エンジニア JOB 就業型インターンで<br>[AbemaTV](https://abema.tv/) Web チームに参加して実際の開発に携わった
- LINE 株式会社 2018 夏インターンシップ エンジニアスクールコースを修了
- 基本情報技術者 を取得
- 第 7 回 立命館大学 全国高校・大学 ソフトウェア創作コンテスト「あいちゃれグローバル 2017」にて、  
  「U18 ワークスアプリケーション賞」と「最優秀賞」を獲得
- 高校でパソコン同好会を設立
