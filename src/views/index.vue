<template>
  <div class="app-container home">
    <el-row class="pl20 pr20 pb20 pt20" :gutter="10">
      <el-col :span="12">
        <el-card shadow="always" style="padding-bottom: 20px;font-size: 14px" >
          <div slot="header">
            <span style="font-size: large;font-weight: bold">Welcome to Ruoyi-wms</span>
          </div>
          <div style="display: flex;align-items: center">
            <div class="first" style="font-size:20px;line-height: 50px;background: linear-gradient(to right, red, blue);-webkit-background-clip: text;color: transparent;">
              若依wms是一套基于若依的wms仓库管理系统，支持lodop和网页打印入库单、出库单。包括仓库/库区/货架管理，出入库管理，客户/供应商/承运商，库存看板、库存记录等功能。
	    </div>
          </div>
        </el-card>
      </el-col>
    </el-row>
  </div>
</template>

<script setup name="Index">
const version = ref('5.2.0')

function goTarget(url) {
  window.open(url, '__blank')
}
</script>

<style scoped lang="scss">
.home {
  blockquote {
    padding: 10px 20px;
    margin: 0 0 20px;
    font-size: 17.5px;
    border-left: 5px solid #eee;
  }
  hr {
    margin-top: 20px;
    margin-bottom: 20px;
    border: 0;
    border-top: 1px solid #eee;
  }
  .col-item {
    margin-bottom: 20px;
  }

  ul {
    padding: 0;
    margin: 0;
  }

  font-family: "open sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  color: #676a6c;
  overflow-x: hidden;

  ul {
    list-style-type: none;
  }

  h4 {
    margin-top: 0px;
  }

  h2 {
    margin-top: 10px;
    font-size: 26px;
    font-weight: 100;
  }

  p {
    margin-top: 10px;

    b {
      font-weight: 700;
    }
  }

  .update-log {
    ol {
      display: block;
      list-style-type: decimal;
      margin-block-start: 1em;
      margin-block-end: 1em;
      margin-inline-start: 0;
      margin-inline-end: 0;
      padding-inline-start: 40px;
    }
  }
}
</style>

