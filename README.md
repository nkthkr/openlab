# NISLAB OpenLAB App

This is [Open LAB Web Site](https://openlab.nislab.info/).

> https://openlab.nislab.info/

## Assets

- Vue.js
  - Vuetify
  - Bootstrap
- Firebase
  - Authentication
  - Realtime Database
  - Hosting
  - Functions
- Node.js

## npm

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

## Firebase CLI

### Firebase CLI のインストール

```
npm install -g firebase-tools
```

### Deploy

```
firebase deploy
```

### 特定の Firebase サービスをデプロイ

```
firebase deploy --only hosting,...
```

| フラグ構文       | デプロイされるサービス/機能         |
| :--------------- | :---------------------------------- |
| --only hosting   | Firebase Hosting のコンテンツ       |
| --only database  | Firebase Realtime Database のルール |
| --only storage   | Cloud Storage for Firebase のルール |
| --only functions | Cloud Functions for Firebase        |
