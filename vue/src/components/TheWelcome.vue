<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
import IconLink from "@/components/icons/IconLink.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>文档</template>

    Vue的
    <a href="https://vuejs.org/" target="_blank" rel="noopener">官方文档</a>
    为你提供了所有您需要的信息开始
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>工具</template>

    该项目由
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener">Vite</a>提供并捆绑.推荐的 IDE 设置是
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener">VSCode</a> +
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener">Volar</a>. 如果您需要测试组件和网页, 请查看
    <a href="https://www.cypress.io/" target="_blank" rel="noopener">Cypress</a> 和
    <a href="https://on.cypress.io/component" target="_blank" rel="noopener">Cypress 组件测试</a>.

    <br />

    更多说明请参阅 <code>README.md</code>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>生态系统</template>

    获取项目的官方工具和库:
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener">Pinia</a>,
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener">Vue Router</a>,
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener">Vue Test Utils</a>, 和
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener">Vue Dev Tools</a>. 如果您需要更多资源, 我们建议您访问
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">Awesome Vue</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>社区</template>

    卡住了？ 在
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Vue Land</a>上提问, 我们的官方
    Discord 服务器, 或
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      >StackOverflow</a
    >. 您还应该订阅
    <a href="https://news.vuejs.org" target="_blank" rel="noopener">our mailing list</a> 并跟随
    官方
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener">@vuejs</a>
   twitter 帐户，了解 Vue 世界的最新消息.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>支持 Vue</template>

    作为一个独立的项目，Vue 的可持续性依赖于社区的支持。 您可以提供帮助
    我们 通过
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">becoming a sponsor</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <IconLink />
    </template>
    <template #heading>其他页面</template>

    去其他页面看看吧
  </WelcomeItem>
</template>
