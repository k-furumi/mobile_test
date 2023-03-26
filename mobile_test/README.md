# Nuxt3モバイル開発テスト

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install
```
### android
android studioのインストールが必要。 https://developer.android.com/studio
インストールし、起動まで確認する。

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```
この時点でブラウザから参照は可能。

androidで動作確認を行うには、以下のコマンドを実行。
- npm run devのnetworkのipをcapacitor.config.jsonのserverのurlに設定(ホットリロードのため)
- USBで端末を接続(要developer mode & USBデバッグ) 
- 以下のコマンドを実施
```bash
 npm run droid
``` 

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
