<template>
  <div>
    <slide-box class="glass-bg box-show" style="width:92%; height:188px; padding:6px; box-sizing:border-box; margin:0 auto 18px;"/>

    <div @touchstart='touchStart' @touchend='touchEnd' style="width:100%;">
      <!-- 推荐作家 -->
      <router-link to="/m/authorList" class="glass-bg box-show" style="width:92%; margin:0 auto 18px; display:inline-block; box-sizing:border-box;">
        <p style="text-align:left; font-size:18px; color:#CCC; border-bottom:1px solid #555; line-height:32px;">
          <i class="MyIF avatar" style="margin:0 8px; font-size:20px; color:#9f8bff;"></i>推荐作者<i class="MyIF double-arrow-right" style="margin-right:18px; float:right; color:#32beff;"></i>
        </p>
        <table style="width:100%; height:58px; margin:6px 0;">
          <tr>
            <td style="width:25%;">
              <router-link to="/m/author" style="width:42px; height:42px; display:inline-block;">
                <img v-lazy="this.$store.state.baseHost + 'img/touxiang.jpg'" style="width:100%; height:100%; border-radius:3px;"/>
              </router-link>
              <router-link to="/m/author" style="min-width:50px; max-width:92%; height:19px; margin:0 auto; display:inline-block; box-shadow:0 0 2px #46dfff; color:#CCC; line-height:20px; font-size:15px;">456</router-link>
            </td>
            <td style="width:25%;">
              <router-link to="/m/author" style="width:42px; height:42px; display:inline-block;">
                <img v-lazy="this.$store.state.baseHost + 'img/touxiang.jpg'" style="width:100%; height:100%; border-radius:3px;"/>
              </router-link>
              <router-link to="/m/author" style="min-width:50px; max-width:92%; height:18px; margin:0 auto; display:inline-block; box-shadow:0 0 2px #46dfff; color:#CCC; line-height:20px; font-size:15px;">456</router-link>
            </td>
            <td style="width:25%;">
              <router-link to="/m/author" style="width:42px; height:42px; display:inline-block;">
                <img v-lazy="this.$store.state.baseHost + 'img/touxiang.jpg'" style="width:100%; height:100%; border-radius:3px;"/>
              </router-link>
              <router-link to="/m/author" style="min-width:50px; max-width:92%; height:19px; margin:0 auto; display:inline-block; box-shadow:0 0 2px #46dfff; color:#CCC; line-height:20px; font-size:15px;">456</router-link>
            </td>
            <td style="width:25%;">
              <router-link to="/m/author" style="width:42px; height:42px; display:inline-block;">
                <img v-lazy="this.$store.state.baseHost + 'img/touxiang.jpg'" style="width:100%; height:100%; border-radius:3px;"/>
              </router-link>
              <router-link to="/m/author" style="min-width:50px; max-width:92%; height:19px; margin:0 auto; display:inline-block; box-shadow:0 0 2px #46dfff; color:#CCC; line-height:20px; font-size:15px;">456</router-link>
            </td>
          </tr>
        </table>
      </router-link>

      <!-- 推荐文章分类 -->
      <router-link to="/m/categoryList" class="glass-bg box-show" style="width:92%; margin:0 auto 18px; display:inline-block; box-sizing:border-box;">
        <p style="text-align:left; font-size:18px; color:#CCC; border-bottom:1px solid #555; line-height:32px;">
          <i class="MyIF music-box" style="margin:0 8px; font-size:20px; color:#9f8bff;"></i>推荐分类<i class="MyIF double-arrow-right" style="margin-right:18px; float:right; color:#32beff;"></i>
        </p>
        <table style="width:100%; height:58px; margin:6px 0;">
          <tr>
            <td style="width:25%;">
              <router-link to="/m/category" style="width:42px; height:42px; display:inline-block;">
                <img v-lazy="this.$store.state.baseHost + 'img/touxiang.jpg'" style="width:100%; height:100%; border-radius:3px;"/>
              </router-link>
              <router-link to="/m/category" style="min-width:50px; max-width:92%; height:19px; margin:0 auto; display:inline-block; box-shadow:0 0 2px #46dfff; color:#CCC; line-height:20px; font-size:15px;">456</router-link>
            </td>
            <td style="width:25%;">
              <router-link to="/m/category" style="width:42px; height:42px; display:inline-block;">
                <img v-lazy="this.$store.state.baseHost + 'img/touxiang.jpg'" style="width:100%; height:100%; border-radius:3px;"/>
              </router-link>
              <router-link to="/m/category" style="min-width:50px; max-width:92%; height:18px; margin:0 auto; display:inline-block; box-shadow:0 0 2px #46dfff; color:#CCC; line-height:20px; font-size:15px;">456</router-link>
            </td>
            <td style="width:25%;">
              <router-link to="/m/category" style="width:42px; height:42px; display:inline-block;">
                <img v-lazy="this.$store.state.baseHost + 'img/touxiang.jpg'" style="width:100%; height:100%; border-radius:3px;"/>
              </router-link>
              <router-link to="/m/category" style="min-width:50px; max-width:92%; height:19px; margin:0 auto; display:inline-block; box-shadow:0 0 2px #46dfff; color:#CCC; line-height:20px; font-size:15px;">456</router-link>
            </td>
            <td style="width:25%;">
              <router-link to="/m/category" style="width:42px; height:42px; display:inline-block;">
                <img v-lazy="this.$store.state.baseHost + 'img/touxiang.jpg'" style="width:100%; height:100%; border-radius:3px;"/>
              </router-link>
              <router-link to="/m/category" style="min-width:50px; max-width:92%; height:19px; margin:0 auto; display:inline-block; box-shadow:0 0 2px #46dfff; color:#CCC; line-height:20px; font-size:15px;">456</router-link>
            </td>
          </tr>
        </table>
      </router-link>

      <div class="glass-bg box-show" style="width:92%; margin:8px auto 0;">
        <p style="text-align:left; font-size:18px; color:#CCC; border-bottom:1px solid #555; line-height:32px;">
          <i class="MyIF information" style="margin:0 8px; font-size:20px; color:#9f8bff;"></i>推荐文章
        </p>

        <article-list />
      </div>
    </div>
  </div>
</template>

<script>
import slideBox from '@/components/base/slideBox.vue'
import articleList from '@/components/article/articleList.vue'

export default {
  name: 'index',

  components: {
    slideBox,
    articleList
  },

  data () {
    return {
    }
  },

  methods: {

    touchStart (ev) {
      ev = ev || event
      if (ev.touches.length === 1) {
        this.startX = ev.touches[0].clientX
      }
    },
    touchEnd (ev) {
      ev = ev || event
      if (ev.changedTouches.length === 1) {
        this.endX = ev.changedTouches[0].clientX
        if ((this.startX <= 38) && ((this.endX - this.startX) >= 68)) {
          this.$store.commit('changeUserMenuShow')
        } else if ((this.startX >= 38) && ((this.startX - this.endX) >= 138)) {
          this.$router.push({ path: '/m/categoryList' })
        } else if ((document.body.clientWidth - this.startX <= 38) && ((this.startX - this.endX) >= 68)) {
          this.$router.push({ path: '/m/search' })
        }
      }
    }
  }
}
</script>

<style scoped>

</style>
