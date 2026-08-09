# AIベンチマーク&リーダーボード集

<p align="center">
  <a href="README.md">English</a> |
  <a href="README.ja.md">日本語</a>
</p>


## 総合比較・ランキング

| 名称 | 説明 |
| --- | --- |
| [Artificial Analysis](https://artificialanalysis.ai/) | AIモデルとAPIプロバイダーを品質・価格・出力速度・レイテンシーなどの指標で独自に比較分析するサイト。独自のインテリジェンス指数や幻覚率評価も提供。 |
| [LLM Stats](https://llm-stats.com/) | 289以上のAIモデルを対象に、ベンチマーク性能・価格・処理速度を独立した再現可能な手法で一元比較するプラットフォーム。言語モデルだけでなく画像・動画・音声生成にも対応。 |
| [Scale Labs Leaderboard](https://labs.scale.com/leaderboard) | Scale社が運営するAIモデル評価プラットフォーム。エージェント能力・先端推論・安全性など複数カテゴリの専門的ベンチマーク（SWE-Bench Pro、Humanity's Last Exam等）を集約。 |
| [Vellum LLM Leaderboard](https://www.vellum.ai/llm-leaderboard) | 主要LLMをGPQA Diamond・AIME・SWE-Bench Verified・ARC-AGIなどの公開ベンチマークに加え、処理速度やコスト効率も含めて一覧比較できるリーダーボード。 |
| [Nejumi Leaderboard 4](https://nejumi.ai/) | Weights & Biases運営の日本語LLM評価リーダーボード。日本語の生成精度に加え、実用的なアプリケーション開発能力と安全性を総合的に評価し、国内向けLLM選定を支援。 |

## ユーザー評価型ランキング

| 名称 | 説明 |
| --- | --- |
| [LM Arena](https://lmarena.ai/ja/leaderboard) | ユーザーがAIモデルの出力を匿名で比較投票し、Eloレーティング方式でランキングを形成するコミュニティ主導プラットフォーム。テキスト・画像・動画生成など幅広いカテゴリに対応。 |
| [Design Arena](https://www.designarena.ai/leaderboard) | AIが生成するデザインを対象としたクラウドソーシング型ベンチマーク。同一プロンプトから生成された出力をユーザーがモデル名を伏せた状態で比較し、そのペアワイズ投票をBradley-Terryモデルによるレーティングに集約する。モダリティごとに別ベンチマークとして分けるのではなく、統合リーダーボード内に[コード](https://www.designarena.ai/leaderboard)・[スライド](https://www.designarena.ai/leaderboard?tab=slides)・[画像](https://www.designarena.ai/leaderboard?tab=image)・[動画](https://www.designarena.ai/leaderboard?tab=video)・[音声](https://www.designarena.ai/leaderboard?tab=audio)・[ビルダー](https://www.designarena.ai/leaderboard?tab=builders)の専用表示を設け、Web／アプリ開発、ゲーム開発、画像・動画編集、音声合成などをさらに細分化して評価する。 |
| [Yupp Leaderboard](https://yupp.ai/leaderboard) | ユーザーコミュニティの評価データに基づきAIモデルをランキングするリーダーボード。実際の利用シーンにおけるモデル品質をコミュニティの集合知で可視化。 |
| [Open WebUI Leaderboard](https://openwebui.com/leaderboard) | オープンソースのLLMフロントエンド「Open WebUI」のコミュニティにおいて、100以上のモデルを実際のユーザー利用・評価データに基づきランキングするリーダーボード。 |

## コーディング・ソフトウェア開発

| 名称 | 説明 |
| --- | --- |
| [DeepSWE](https://deepswe.datacurve.ai/) | 最先端のコーディングエージェントを、独創的で長期的なエンジニアリングタスクで評価する。 |
| [SWE-rebench](https://swe-rebench.com/) | 定期的に新しい課題を更新し、時間ウィンドウ分析でデータ汚染を検出・排除する仕組みを備えたソフトウェアエンジニアリングベンチマーク。SWE-benchの汚染問題を解決するために設計。 |
| [SWE-Bench Pro（Public）](https://labs.scale.com/leaderboard/swe_bench_pro_public) | Scale社が提供する1,865タスクの大規模ベンチマーク。コピーレフトライセンスのコードを使用してデータ汚染を排除し、B2B・消費者向けアプリ・開発者ツールなど多様な実務課題でAIの問題解決力を厳密に評価する公開データセット版。 |
| [SWE-bench](https://www.swebench.com/) | DjangoやMatplotlibなど実在OSSプロジェクトのGitHub Issueを用いて、AIがバグ修正や機能実装をどの程度解決できるかを測定するベンチマーク。Verified・Multilingual・Multimodalなど複数バリエーションを提供。 |
| [Convex LLM Leaderboard](https://www.convex.dev/llm-leaderboard/with-guidelines) | Convexプラットフォーム向けのコード生成品質を評価するリーダーボード。ガイドライン提供の有無による性能差を比較でき、実務でのプロンプト設計の効果を測定可能。 |

## AIエージェント

| 名称 | 説明 |
| --- | --- |
| [Terminal-Bench](https://www.tbench.ai/) | ソフトウェア開発・ML・セキュリティ・データサイエンスなど多領域のタスクで、AIエージェントのターミナル操作能力を成功率で評価するベンチマーク。 |
| [SanityHarness](https://sanityboard.lr7.dev/) | Dart・Go・Kotlin・Rust・TypeScript・Zigなど複数言語の26タスクで、AIコーディングエージェントを難易度に応じた加重スコアで評価する高信頼性リーダーボード。 |
| [τ-bench](https://taubench.com/#leaderboard) | 航空会社や小売業などの業務シナリオをシミュレーションし、AIエージェントがユーザーと対話しながらタスクを遂行する能力を測定するベンチマーク。 |

## 数学・推論

| 名称 | 説明 |
| --- | --- |
| [FrontierMath](https://epoch.ai/frontiermath/tiers-1-4?view=graph&tab=leaderboard&tier=Core+%28Tiers+1-3%29) | Epoch AIが開発した、学部レベルから未解決の研究課題まで段階的に難易度が上がる数学問題でAIの高度な数学推論能力を測定するベンチマーク。 |

## 創作・ロールプレイ

| 名称 | 説明 |
| --- | --- |
| [Japanese-RP-Bench](https://github.com/tegnike/Japanese-RP-Bench) | 日本語ロールプレイLLMの会話品質・役柄への追従性・人格の安定性・人格置換や誤誘導への耐性・その後の復帰力を評価するベンチマーク。v2では従来の30ロール・10往復の基本評価を維持しつつ、敵対的なチャレンジシナリオを追加。 |
| [Hemingway-bench](https://surgehq.ai/benchmarks/hemingway-bench) | クリエイティブ・ビジネス・日常の文章作成タスクを、プロの作家が評価するベンチマーク兼リーダーボード。凝った比喩など一見した表面的な印象ではなく、本当に優れた文章を評価することを目指し、センス・独創性・一貫性・感情知性を重視する。 |
| [LLM Creative Story-Writing Benchmark](https://github.com/lechmazur/writing) | 同じ制約付きの創作課題に対する短編を比較するベンチマーク。各作品には、人物・物・概念・属性・行動・方法・舞台・時代設定・動機・トーンという10個の必須要素を意味のある形で盛り込むことが求められる。条件を揃えた作品ペアを評価モデルが比較し、その勝敗を相対比較スコアに集約する方式で、プロンプト・生成作品・不確実性区間・語数遵守などの診断情報も公開している。 |
| [EQ-Bench Longform Creative Writing](https://eqbench.com/creative_writing_longform.html) | 最小限のプロンプトから物語を企画し、計画を振り返って修正したうえで、約1,000語の章を8回にわたって長編として書く能力を評価する、LLM判定型のベンチマーク。多面的な人物描写・感情への訴求・筋・一貫性・トーン・人物設定の維持・計画とプロンプトへの忠実さに加え、弱い会話、説明過多、陳腐さ、未熟な文章、華美な文体、不自然な比喩などを採点し、反復・LLM特有の表現（Slop）・章を重ねた際の品質劣化も可視化する。 |
| [EQ-Bench Creative Writing](https://eqbench.com/creative_writing.html) | 32種類のプロンプトに対する創作文を、LLMによるルーブリック採点とペアワイズ比較に基づく修正版Glickoレーティングの両方で評価するリーダーボード。独創性・人物描写・一貫性・指示追従などに加え、反復表現やLLM特有の常套句（Slop）の使用傾向も可視化。 |
| [Arena Creative Writing Leaderboard](https://arena.ai/leaderboard/text/creative-writing) | オープンエンドな創作文タスクを対象とするText Arenaのコミュニティ評価型ランキング。匿名のユーザー投票による比較結果をElo方式のスコアに反映し、モデルごとの投票数や不確実性も表示する。多数のモデルを継続的に横断比較できる一方、固定ルーブリックや単一の再現可能なテストセットではなく、ユーザーの選好を反映するランキングである点に注意が必要。 |

## サイバーセキュリティ

| 名称 | 説明 |
| --- | --- |
| [DeepSecBench](https://vercel.com/ai-gateway/leaderboards/deepsecbench) | DeepSecのサイバーハーネスを用いて、AIモデルがアプリケーションコード内のセキュリティ脆弱性を発見する能力を測定するリーダーボード。再現率と適合率を統合したスコアに加え、誤検知数・コスト・実行時間も比較。 |

## 埋め込みモデル

| 名称 | 説明 |
| --- | --- |
| [MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard) | Massive Text Embedding Benchmarkの略。テキスト埋め込みモデルの性能を複数のタスク・言語にわたって標準化された手法で評価・比較するHugging Face上のリーダーボード。 |
| [MMEB Leaderboard](https://huggingface.co/spaces/TIGER-Lab/MMEB-Leaderboard) | TIGER-Lab運営のMultimodal Embedding Benchmarkリーダーボード。テキストと画像を統一的な埋め込み空間で表現するマルチモーダル埋め込みモデルの性能を比較・評価。 |

## 音声認識

| 名称 | 説明 |
| --- | --- |
| [Open ASR Leaderboard](https://huggingface.co/spaces/hf-audio/open_asr_leaderboard) | Hugging Faceが運営する自動音声認識（ASR）モデルのリーダーボード。複数のデータセットを用いて音声認識の精度を横断的に比較・評価。 |
