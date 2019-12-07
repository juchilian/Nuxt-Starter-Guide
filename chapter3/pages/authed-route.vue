<template lang="pug">
  div
    h2 認証が必要なページ
    p Cookie の 'credential' 値がTruthyな場合のみアクセス可能です。
    br
    nuxt-link(to="/") トップページへ戻る
</template>