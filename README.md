## What is This?
OpenAI-WhisperをつかってDiscordの音声通話の文字起こしをするBot
> [!NOTE]
> VADやノイズ除去の事前処理がまだ足りない節があります。

#### Features
- /join --- ボイスチャットに参加させるコマンド
- /leave --- ボイスチャットから退室させるコマンド
- ボイスチャットが0人になると自動退室する機能
- Teamsのように、誰がったかわかりやすい表示方法(WebHook)
  - 気が向いたらONOFFできるように
- 退室時のレポート機能
  - 気が向いたらONOFFできるように

## How to Use?
#### Env
```
BOT_TOKEN=
GUILD_ID=
```

#### Install
```
npm install
npx nodejs-whisper download
```
> [!NOTE]
> nodejs-whisperにWhisper部分の動作は依存しています。
> 該当ライブラリのインストール手順を参照ください。

#### Run
```
npm run start
```


