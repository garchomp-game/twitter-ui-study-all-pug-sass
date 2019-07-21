<template lang="pug">
div
  header
    .container
      .left-group
        ul.category
          li.acitve
            font-awesome-icon.icon(icon="home")
            span ホーム
          li
            font-awesome-icon.icon(icon="home")
            span モーメント
          li
            font-awesome-icon.icon(icon="home")
            span 通知
          li
            font-awesome-icon.icon(icon="home")
            span メッセージ
      .center-group
        img(:src="twitter")
      .right_group
        label.form
          input(placeholder="キーワード検索")
          font-awesome-icon.button(icon="search")
        img.icon(:src="userIcon")
        button.tweet_button ツイート
  .container
    .hogehogeee
</template>

<script>
import userIcon from '@/assets/img/userIcon.jpg'
import twitter from '@/assets/img/twitter.png'
export default {
  data() {
    return {
      userIcon: userIcon,
      twitter: twitter
    }
  }
}
</script>

<style lang="scss">
.form {
  input {

  }
  .button {

  }
}
</style>
