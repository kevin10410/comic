<template lang="pug">
  .home
    .home__container
      img.home__cover(src="https://hexschool.github.io/THE_F2E_Design/week5-comic%20viewer/assets/comic%20cover.png")
      .home__main
        p.home__main--title MY HEXSCHOOL
        .home__main--info
          p
            span.subtitle  Genres
            span.value Fusce/vehicula/dolor
          p
            span.subtitle  Author
            span.value Namae Shiranai
          p
            span.subtitle  Status
            span.value Ongoing
          p
            span.subtitle  Rate
            span.value
              span.star <i class="fas fa-star"></i>
              span.star <i class="fas fa-star"></i>
              span.star <i class="fas fa-star"></i>
              span.star <i class="fas fa-star"></i>
              span.star <i class="far fa-star"></i>
          p.summary Summary
          p.content If your banker breaks, you snap; if your apothecary by mistake sends you poison in your pills, you die.
          br
          p.content Therefore, I say, I saw that this situation of mine was the precise situation of every mortal that has this Siamese connexion with a plurality of other mortals.
    .home__bottomTitle All Chapters
    .home__chapters
      p.home__chapters--item Chapter 1: The F2E Challenge Start!
      p.home__chapters--item Chapter 2: Todo List is Going Crazy!
        span.newIcon NEW
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss" scoped>
  .home {
    padding: 25px 202px 50px 202px;
    &__container {
      display: flex;
    }
    &__cover {
      width: 300px;
      height: 446px;
      border: 4px solid #000000;
      box-sizing: border-box;
    }
    &__main {
      width: 320px;
      &--title {
        font-size: 36px;
        color: #FFFFFF;
        font-weight: bold;
        padding: 8px;
        text-align: center;
        background: #000000;
      }
      &--info {
        padding-top: 16px;
        padding-left: 20px;
        p {
          margin-top: 8px;
          font-size: 16px;
          color: #000000;
          padding: 4px 0;
          .subtitle {
            display: inline-block;
            width: 52px;
            font-weight: bold;
          }
          .value {
            margin-left: 20px;
            .star {
              margin-right: 10px;
            }
          }
          &:first-child {
            margin-top: 0;
          }
        }
        .summary {
          font-weight: bold;
        }
        .content {
          margin: 0;
          line-height: 24px;
        }
      }
    }
    &__bottomTitle {
      display: inline-block;
      margin-top: 24px;
      padding: 8px 24px;
      font-size: 24px;
      font-weight: bold;
      color: #FFFFFF;
      background: #000000;
    }
    &__chapters {
      background: #FFFFFF;
      border: 4px solid #000000;
      padding: 22px 24px;
      width: 100%;
      box-sizing: border-box;
      &--item {
        padding: 4px 0;
        font-size: 16px;
        font-weight: bold;
        .newIcon {
          margin-left: 16px;
          padding: 2px 12px;
          font-size: 14px;
          color: #000000;
          background: #50FF44;
        }
        &:last-child {
          margin-top: 15px;
        }
      }
    }
  }
</style>
