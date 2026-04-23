# Anti-Gravity Saga — カット割り・素材マッピング表 v1

**作成日**: 2026-04-17  
**用途**: P-05 各カットと既存WebP素材のひも付け + 制作タスク分類  
**参照**: storyboard_v1.md / images/ ディレクトリ（全46枚）  

---

## 凡例

```
状態:
  ✅ 既存素材そのまま使用可
  🔧 既存素材を加工（クロップ / ケラレ除去 / 合成）
  🎬 AI Img2Video で動画生成（D-02）
  ✨ After Effects / パーティクル合成（D-03 / D-04）
  🆕 新規制作（AI生成静止画 or 手描き）

タスク:
  D-01: KVレイヤー分解
  D-02: AI Img2Video 生成
  D-03: After Effects モーションコミック化
  D-04: パーティクル・エフェクト
  D-05: リップシンク生成
  D-06: ロゴ・タイトルアニメーション
```

---

## 全カット一覧

| C# | 尺 | 状態 | 素材ファイル（images/） | 加工・タスク | 音楽/SE |
|---|---|---|---|---|---|
| **SCENE 1 コールドオープン** | | | | | |
| C001 | 3s | ✅ | ─（黒画面） | フェードイン処理のみ | なし |
| C002 | 4s | 🎬 | world_floating.webp | AI動画化 / 地平線出現アニメ | BGM_01 pppp |
| C003 | 5s | 🎬 | world_floating.webp | AIパン / 島々の全景・朝焼け | BGM_01 |
| C004 | 4s | 🎬 | world_city.webp | AI動画化 / 霧の中の廃墟ビル群 | SE_01 |
| C005 | 3s | 🔧 | world_map.webp | ZOOM in のみ（D-03） | なし |
| C006 | 3s | 🔧 | world_city.webp | ルカのシルエット合成（luca_concept.webp を暗くして小さく合成） | ナレ① |
| C007 | 3s | 🎬 | world_city.webp | ルカシルエットへDOLLY前進 | ナレ② |
| **SCENE 2 タイトル** | | | | | |
| C008 | 15s | 🆕 | ─（黒背景） | ロゴアニメーション（D-06）。「Anti-Gravity Saga / 黄昏のルカと暁のエルフ」2段階出現 | BGM_06 |
| **SCENE 3 第1章圧縮** | | | | | |
| C009 | 5s | 🎬 | kv01_gray_daily.webp | AI PANまたはパララックス。早朝廃墟+霧 | BGM_01, SE_01 |
| C010 | 5s | 🔧 | kv03_scavenging.webp | D-03 パララックス / ルカが作業する動き | なし |
| C011 | 3s | 🔧 | kv01_gray_daily.webp | ルカの後ろ姿クロップ + 周囲住民の視線（luca_concept.webp 活用） | ナレ③ |
| C012 | 4s | 🔧 | kv01_gray_daily.webp + world_floating.webp | TILT上 / ルカが空を見上げる → 空合成 | ナレ④ |
| C013 | 3s | ✅ | world_floating.webp | スロー ZOOM out | なし |
| C014 | 5s | 🎬 | kv03_scavenging.webp | AI DOLLY 前進 / 森入り口 | BGM_01→BGM_02 XF |
| C015 | 5s | 🔧 | world_forest.webp | 発光する苔の青緑ライト合成（D-04） | SE_02 |
| C016 | 5s | 🎬 | world_forest.webp | ルカの後ろ姿合成 → AI動画化 | SE_02 続き |
| C017 | 5s | 🎬 | scene_01_meeting.webp | AI DOLLY 前進 / 木漏れ日のライト追加（D-04） | BGM_02 |
| C018 | 3s | 🔧 | scene_01_meeting.webp | ZOOM in クローズアップ（顔部分クロップ） | ナレ⑤ |
| C019 | 2s | 🔧 | scene_01_meeting.webp + luca_concept.webp | ルカの手を前景に合成 | BGM_06 一瞬 |
| **SCENE 4 第2章前半** | | | | | |
| C020 | 5s | ✅ | scene_02_restaurant.webp | FIX / 窓の光エフェクト（D-04） | BGM_03 開始 |
| C021 | 5s | 🔧 | scene_02_restaurant.webp | D-01 レイヤー分解後、内部PAN | BGM_03 |
| C022 | 4s | 🔧 | scene_02_restaurant.webp | D-01 マーサ部分クロップ。D-05 リップシンク | マーサ台詞 |
| C023 | 3s | 🔧 | scene_02_restaurant.webp | D-01 ルカ+シルアの配置カット | 台詞 |
| C024 | 3s | 🔧 | scene_02_restaurant.webp + silua_expressions.webp | シルアの目が開くアニメ（D-03）。D-05 リップシンク | 台詞 |
| C025 | 5s | 🔧 | scene_02_restaurant.webp | 湯気パーティクル合成（D-04）。シルア独り言 | シルア独り言 |
| C026 | 5s | 🔧 | silua_expressions.webp（驚き/笑顔表情） | D-03 表情変化アニメ | なし |
| C027 | 3s | 🔧 | scene_02_restaurant.webp（ルカ横顔クロップ） | D-03 パララックス | マーサ台詞 |
| C028 | 5s | 🔧 | scene_02_restaurant.webp | D-01 分解 / マーサ笑顔切り替え。D-05 リップシンク | 台詞 |
| C029 | 5s | 🔧 | world_city.webp（夜バージョン） | 夜景カラーグレード + 浮遊島合成（world_floating） | BGM_03 FO |
| C030 | 2s | 🔧 | world_floating.webp | 夜バージョン + カラーグレード | なし |
| **SCENE 5 第2章クライマックス** | | | | | |
| C031 | 8s | ✅ | kv02_moonlit_float.webp | FIX / 星のチラツキ合成（D-04） | 環境音のみ |
| C032 | 4s | 🔧 | kv02_moonlit_float.webp | シルアが出てくる動き。ルカが驚く（表情合成） | 台詞 |
| C033 | 3s | 🔧 | kv02_moonlit_float.webp | 二人並ぶポジション調整（luca_silua_adjust.webp参照） | なし |
| C034 | 5s | ✅ | kv02_moonlit_float.webp | TILT up スロー / 空を見上げる | なし |
| C035 | 5s | 🔧 | kv02_moonlit_float.webp + silua_expressions.webp | シルアが目を閉じる → ZOOM in。口元アニメ | 歌 pppp 開始 |
| C036 | 5s | ✨ | kv02_moonlit_float.webp | 石の浮遊パーティクル（D-04）。SE_03 | 歌 p |
| C037 | 5s | ✨ | kv02_moonlit_float.webp | 水滴・緑光パーティクル（D-04）。SE_04, SE_05 | 歌 mp |
| C038 | 5s | 🔧 | kv02_moonlit_float.webp + luca_expressions.webp | ルカのクローズアップ。目が見開かれる表情差し替え | なし |
| C039 | 5s | 🔧 | kv02_moonlit_float.webp | 俯瞰気味 / DOLLY後退 / パーティクル持続（D-04） | なし |
| C040 | 5s | 🔧 | luca_silua_adjust.webp（手元クロップ） | 手が開く動き（D-03 フレームバイフレーム） | ナレ⑥ |
| C041 | 5s | 🔧 | kv02_moonlit_float.webp + silua_expressions.webp | シルアの横顔クロップ。穏やかな表情 | 歌 FO。ナレ⑦ |
| C042 | 3s | ✨ | kv02_moonlit_float.webp | 石がゆっくり落下するパーティクル逆再生 | なし |
| **SCENE 6 第10章フラッシュ** | | | | | |
| C043 | 2s | 🎬 | scene_03_awakening.webp | AI動画化 / 浮遊 + オーラエフェクト（D-04） | BGM_05 強打 |
| C044 | 1s | 🔧 | kv13_chain_cutter.webp | ZOOM in / 赤いビームエフェクト（D-04） | BGM_05 |
| C045 | 2s | 🔧 | kv06_grave_arrival.webp | 闇の中から義眼が光る演出（D-04 グロウエフェクト） | BGM_05 |
| C046 | 2s | 🎬 | kv16_fusion.webp | AI動画化 / PAN。後方から迫る何か | BGM_05 |
| C047 | 2s | ✅ | ─（黒画面） | フラッシュカット終了 | BGM_05 停止 |
| C048 | 3s | ✅ | kv02_moonlit_float.webp | FIX / 静寂の戻り | SE_07 歌の残響 |
| C049 | 5s | 🔧 | kv02_moonlit_float.webp + silua_expressions.webp | シルアの独り言。口元アニメ（D-03） | 台詞 |
| C050 | 10s | 🔧 | kv02_moonlit_float.webp + luca_expressions.webp | ルカが空を見上げる。表情変化が極めて微妙（D-03） | なし |
| **SCENE 7 余韻** | | | | | |
| C051 | 5s | ✅ | luca_silua_adjust.webp | FIX / 夜明けのカラーグレード | BGM_04 開始 |
| C052 | 5s | 🔧 | world_floating.webp | 夜明けのカラーグレード / TILT up | BGM_04 |
| C053 | 8s | 🔧 | luca_silua_adjust.webp + luca_expressions.webp | ルカのクローズアップ。表情変化（微妙な硬直→諦め）| BGM_04 |
| C054 | 7s | 🔧 | luca_silua_adjust.webp + luca_expressions.webp | ほんの少しだけ口元が緩む表情差し替え（本作の感情的ピーク） | BGM_04 |
| C055 | 5s | 🎬 | hero.webp | AI動画化 / DOLLY後退 / 朝露エフェクト（D-04） | BGM_04 FO |
| **SCENE 8 ティザー＆クロージング** | | | | | |
| C056 | 0.5s | ✅ | kv04_ominous_shadow.webp | FIX | BGM_07 開始 ffff |
| C057 | 0.5s | ✅ | kv05_martha_confession.webp | FIX | BGM_07 |
| C058 | 0.5s | ✅ | kv07_subway_chase.webp | FIX | BGM_07 |
| C059 | 0.5s | ✅ | kv08_sky_archipelago.webp | FIX | BGM_07 |
| C060 | 0.5s | ✅ | kv09_memory_light.webp | FIX | BGM_07 |
| C061 | 0.5s | ✅ | kv10_ruined_lab.webp | FIX | BGM_07 |
| C062 | 0.5s | ✅ | kv11_grave_memory.webp | FIX | BGM_07 |
| C063 | 0.5s | ✅ | kv12_gate_song.webp | FIX | BGM_07 |
| C064 | 0.5s | ✅ | kv13_chain_cutter.webp | FIX | BGM_07 |
| C065 | 0.5s | ✅ | kv14_mother_reunion.webp | FIX | BGM_07 |
| C066 | 0.5s | ✅ | kv15_inherited_song.webp | FIX | BGM_07 |
| C067 | 0.5s | ✅ | kv16_fusion.webp | FIX | BGM_07 |
| C068 | 0.5s | ✅ | scene_04_confrontation.webp | FIX | BGM_07 |
| C069 | 0.5s | ✅ | kv17_extended_hand.webp | FIX | BGM_07 |
| C070 | 0.5s | ✅ | kv18_return_to_sky.webp | FIX | BGM_07 |
| C071 | 0.5s | ✅ | kv02_moonlit_float.webp | FIX（再登場 / 繋ぎ） | BGM_07 |
| C072-A | 2s | ✅ | ─（黒背景 + テキスト） | 「空が落ちた世界で──」 | BGM_07 余韻 |
| C072-B | 3s | ✅ | ─（黒背景 + テキスト） | サイトURL + Newsletter CTA | BGM_07 FO |

---

## 状態別集計

| 状態 | カット数 | 比率 | 説明 |
|---|---|---|---|
| ✅ 既存素材そのまま | 26 | 36% | 主にティザーフラッシュ・黒背景 |
| 🔧 既存素材加工 | 30 | 42% | クロップ・合成・パララックスが中心 |
| 🎬 AI Img2Video | 10 | 14% | 動きのある主要シーン |
| ✨ パーティクル合成 | 4 | 5% | SCENE5の浮遊エフェクト群 |
| 🆕 新規制作 | 1 | 1% | ロゴアニメ（D-06） |

**AI動画生成が必要なカット（D-02優先順）**

| 優先 | C# | 素材 | 理由 |
|---|---|---|---|
| ★★★ 最優先 | C002, C003 | world_floating | コールドオープン冒頭。視聴者の第一印象 |
| ★★★ 最優先 | C036〜C042 | kv02_moonlit_float | 本作の最大フック（浮遊エフェクト）|
| ★★ 高 | C043, C046 | scene_03_awakening, kv16_fusion | 第10章フラッシュのインパクト |
| ★★ 高 | C055 | hero | 余韻の〆カット |
| ★ 中 | C004, C007 | world_city | オープニング廃墟演出 |
| ★ 中 | C014, C016 | kv03_scavenging, world_forest | 森への侵入シーン |

---

## 既存素材の使用回数ランキング

| 素材 | 使用カット数 | 主な用途 |
|---|---|---|
| kv02_moonlit_float.webp | 13カット | SCENE 5・6全体 |
| world_floating.webp | 6カット | コールドオープン・空のインサート |
| world_city.webp | 4カット | 廃墟街シーン |
| scene_02_restaurant.webp | 7カット | 食堂シーン |
| luca_silua_adjust.webp | 3カット | 余韻シーン |
| kv01_gray_daily.webp | 3カット | ルカの日常 |
| kv03_scavenging.webp | 2カット | 巨鋼の森 |
| scene_01_meeting.webp | 3カット | 邂逅 |
| silua_expressions.webp | 4カット | シルアの表情差し替え |
| luca_expressions.webp | 3カット | ルカの表情差し替え |

---

## D-01（レイヤー分解）優先対象

以下の素材は複数アングル・表情差し替えが必要なため、Photoshopレイヤー分解を先行させる。

| 素材 | 分解目的 | 使用カット |
|---|---|---|
| scene_02_restaurant.webp | 背景・マーサ・ルカ・シルアを分離 → 各アングル合成 | C021〜C028 |
| kv02_moonlit_float.webp | 背景（空）・屋根・人物を分離 → カメラ移動・パーティクル合成 | C031〜C042 |
| kv01_gray_daily.webp | 背景・ルカを分離 → 視線方向変更可能に | C009〜C012 |

---

## 未使用素材（パイロット版で未使用）

以下は本編用素材として温存。ティザーフラッシュ以外では使わない。

- char_designs_abc.webp（キャラデザ比較シート）
- grave_expressions.webp / grave_sheet.webp（グレイヴ詳細：C045のみ）
- lilia_expressions.webp / lilia_sheet.webp（リリア：本編第9章用）
- main_chars_group.webp / multi_expressions.webp（グループショット）
- world_city_border.webp, world_house.webp, world_lookdev.webp, world_highway.webp
- silua_sheet.webp / silua_sheet_v2.webp（詳細キャラシート）
- martha_expressions.webp / martha_sheet.webp（マーサ詳細）
- luca_concept.webp（C006合成用に一部使用）

---

## 次工程への引き継ぎ

| タスク | 対象カット | 担当工程 |
|---|---|---|
| D-01 レイヤー分解（3素材） | scene_02 / kv02 / kv01 | M0〜M2先行着手 |
| D-02 AI動画生成（★★★優先10カット） | C002,C003,C036〜C042,C043,C046,C055 | M2〜M4 |
| D-03 AE モーションコミック化（30カット） | 加工カット全体 | M2〜M5 |
| D-04 パーティクル（最優先: 浮遊エフェクト） | C036〜C042, C015, C017 | M2〜M4 |
| D-05 リップシンク | C022, C024, C028, C049 | M3〜M4 |
| D-06 ロゴアニメ | C008 | M2（外注） |
