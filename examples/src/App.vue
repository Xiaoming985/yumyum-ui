<template>
  <div>
    <div>Hello, PNPM + Monorepo + Vite</div>
    <yum-button>默认按钮</yum-button>
    <yum-button type="primary">主要按钮</yum-button>
    <yum-button type="success">成功按钮</yum-button>
    <yum-button type="info">信息按钮</yum-button>
    <yum-button type="warning">警告按钮</yum-button>
    <yum-button type="danger">危险按钮</yum-button>
    <yum-button type="primary" loading>loading...</yum-button>
    <yum-button type="success" icon="yum-icon-check_circle">
      带图标按钮
    </yum-button>
    <div>
      <yum-icon name="loading" />
      <i class="yum-icon-loading"></i>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style lang="scss" scoped></style>
