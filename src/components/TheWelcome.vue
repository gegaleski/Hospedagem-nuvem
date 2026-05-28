<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'

const openReadmeInEditor = () => fetch('/__open-in-editor?file=README.md')
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Documentation</template>

    O agronegócio, setor vital para a economia global, enfrenta desafios crescentes como o
    aumento da população mundial, mudanças climáticas e a necessidade de práticas mais
    sustentáveis. Nesse cenário, a incorporação de tecnologias avançadas tornou-se uma estratégia
    indispensável para atender às demandas por eficiência e produtividade, e conceitos como a Internet
    das Coisas (IoT), Integração Vertical e Horizontal, e Tecnologia da Informação estão remodelando
    a forma como o agronegócio opera, possibilitando um gerenciamento mais integrado e orientado
    por dados. Esses avanços tecnológicos promovem não apenas ganhos de eficiência, mas também
    fortalecem a sustentabilidade ambiental e a segurança alimentar.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tooling</template>

    Em uma região com forte tradição agrícola, uma cooperativa de produtores enfrenta desafios
    crescentes para atender às demandas do mercado. A competitividade no setor está cada vez mais
    acirrada, exigindo maior produtividade, redução de desperdícios e adaptação às exigências de
    sustentabilidade. Além disso, os consumidores estão cada vez mais exigentes, demandando
    rastreabilidade dos produtos, qualidade garantida e práticas de produção responsáveis.

    <br />

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Ecosystem</template>

    A cooperativa, composta por pequenos e médios produtores, percebe que as abordagens
    tradicionais de gestão e operação não são mais suficientes. A falta de integração entre os elos da
    cadeia produtiva, tanto no nível interno (entre os produtores) quanto externo (com fornecedores,
    distribuidores e clientes), dificulta a tomada de decisões estratégicas e a criação de uma operação
    eficiente.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>

    Got stuck? Ask your question on
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Vue Land</a>
    (our official Discord server), or
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener">StackOverflow</a>. You
    should also follow the official
    <a href="https://bsky.app/profile/vuejs.org" target="_blank" rel="noopener">@vuejs.org</a>
    Bluesky account or the
    <a href="https://x.com/vuejs" target="_blank" rel="noopener">@vuejs</a>
    X account for latest news in the Vue world.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Vue</template>

    As an independent project, Vue relies on community backing for its sustainability. You can help
    us by
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">becoming a sponsor</a>.
  </WelcomeItem>
</template>
