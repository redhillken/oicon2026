# oicon2026

追いコンムービー（VIVANTオマージュ）の冒頭用、ハッキング風演出（ブラウザで動くジョーク演出です。実際のハッキングは一切行いません）。

▶ 遊ぶ: https://redhillken.github.io/oicon2026/

## 遊び方

1. `index.html` をブラウザで開く（GitHub Pages を有効にしている場合はそのURLを開く）
2. 最初にキーを押すか画面をクリックした瞬間に全画面になります
3. パスワード画面で `oicont` と入力して Enter
4. テレビが消えるような演出のあと、約16秒のハッキング演出が始まり「ACCESS GRANTED」で完了

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
