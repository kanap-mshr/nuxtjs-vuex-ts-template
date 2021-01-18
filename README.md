
# template-pj

- これは、テンプレートプロジェクトです

---

## Build Setup

```bash
# モジュールインストール
yarn install

# ローカルで起動
yarn dev

# buildとstart
yarn build
yarn start

# 静的なウェブアプリケーションを生成
yarn generate
```

- 参考: [Nuxt.js docs](https://nuxtjs.org)

---

## nuxt(vuex)のtypescript化への道のり

- 前提
  - 型推論が100%完璧ではないが完璧を目指すのは茨の道、とのこと。
  - ある程度妥協して、まあ使えるよね、程度の環境構築を以下に示す

- Nuxtプロジェクトの生成

```bash
npx create-nuxt-app <PJ_NAME>
```


