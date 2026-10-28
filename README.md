# oicon2026

追いコンムービー（VIVANTオマージュ）の冒頭用、ハッキング風演出（ブラウザで動くジョーク演出です。実際のハッキングは一切行いません）。

▶ 遊ぶ: https://redhillken.github.io/oicon2026/

## 遊び方

1. ページをブラウザで開く（全画面にしたいときはブラウザのキオスクモード／F11 で表示。画面は 16:9 の枠で表示されます）
2. パスワード画面で `oicont` と入力して Enter
3. テレビが消えるような演出のあと、約16秒のハッキング演出が始まり「ACCESS GRANTED」で完了
4. 最後にテレビが消えるように暗転して終わります

## カスタマイズ

`index.html` 内の以下を書き換えると調整できます。

- `PASSWORD` … 合言葉
- `HACK_MS` … ハッキング演出の長さ（ミリ秒）

## 効果音

`sfx/` フォルダの音源と、ブラウザで合成する重低音・警報・衝撃音を組み合わせています。
ハッキング中は低いうなりが心拍のように脈打ちながら速くなり、ライザー音が ACCESS GRANTED の瞬間に頂点を迎えます。
音を消したいときは `index.html` の `SOUND = true` を `false` にしてください。

### 音源クレジット
- Pixabay: koiroylers「glitch zap」/ kuzu420「err」/ lucadialessandro「little alien」/ soumages「glitchy sound」/ u_l2ubb7ipxx「bell riser」
- ElevenLabs で生成した効果音（ターミナル起動音・通信ノイズ）
