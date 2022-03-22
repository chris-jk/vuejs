<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Demos</template>

    <p style="text-align: center"><a href="../../crm">CRM</a></p>
    <p style="text-align: center"><a href="../../analytics">Analytics</a></p>
    <p style="text-align: center"><a href="../../videos">Videos</a></p>
    <p style="text-align: center"><a href="../../multi-shop">Multi-Shop</a></p>
    <p style="text-align: center"><a href="../../endo">Endo</a></p>
    <p style="text-align: center">
      <a href="../../strain-guide">StrainGuide</a>
    </p>
    <p style="text-align: center"><a href="../../">you-stagram</a></p>
    <p style="text-align: center">
      <a href="https://github.com/chris-jk"
        ><i style="font-size: 24px" class="fa">&#xf09b;</i></a
      >
    </p>
  </WelcomeItem>
</template>

<style scoped>
.greetings {
  text-align: center;
}
</style>
