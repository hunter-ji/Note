<template>
  <div class="container">
    <div class="content">
      事实上，一个网站是一个由驱动的单页应用。如果你以前使用过
      的话，当你在开发一个自定义主题的时候，你会感受到非常熟悉的开发体验，你甚至可以使用
      去调试你的自定义主题。
      事实上，一个网站是一个由驱动的单页应用。如果你以前使用过
      的话，当你在开发一个自定义主题的时候，你会感受到非常熟悉的开发体验，你甚至可以使用
      去调试你的自定义主题。
    </div>
  </div>
</template>

<script>
export default {
  name: "Home"
};
</script>

<style scoped>
.container {
  width: 50%;
  min-height: 50%;
  max-height: 100%;
  background: #ffffff;
  box-shadow: 0 2px 12px 0 rgba(0, 0, 0, 0.1);
  border-radius: 0.25rem;
  background-clip: border-box;
  border: 1px solid rgba(0, 0, 0, 0.125);
}

.content {
  margin: 96px;
  animation: card-enter 2s;
  -webkit-animation: card-enter 2s;
}

@-webkit-keyframes card-enter {
  0% {
    opacity: 0;
    transform: translateY(-30px);
  }
  100% {
    opacity: 1;
  }
}
</style>
