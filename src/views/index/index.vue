<template>
  <div class="index-container"></div>
</template>

<script>
export default {
  name: "Index",
  components: {},
  data() {
    return {};
  },
  created() {},
  mounted() {},
  methods: {},
};
</script>

<style lang="scss" scoped>
.index-container {
  ::v-deep {
    .el-card__body {
      > div {
        min-height: 70vh;
        padding: 20px;

        > ul {
          > li {
            line-height: 30px;
          }
        }

        > img {
          display: block;
          margin: 40px auto;
          border: 1px solid #dedede;
        }
      }
    }
  }
}
</style>
