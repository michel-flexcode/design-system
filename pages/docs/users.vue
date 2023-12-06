<script setup>
definePageMeta({
  layout: "docs",
});
</script>

<template>
  <Container>
    <TitresH1> Users </TitresH1>

    <TextesParagraphe>
      Vous pouvez utilisez les users de Remix Icon dans vos projets.

      <LinksExternal to="https://remixicon.com/"
        >https://remixicon.com/</LinksExternal
      >
    </TextesParagraphe>

    <TitresH2>Exemples</TitresH2>

    <i class="ri-user-fill"></i>

    <TextesCode :code="`< i class=&quot;ri-user-fill&quot;></i> `" />

    <TitresH2>Affichage</TitresH2>

    <ListsGrid class="mt-12 mb-4">
      <li><Image src="/img/test.png" alt="test" /></li>
      <li><Image src="/img/test.png" alt="test" /></li>
      <li><Image src="/img/test.png" alt="test" /></li>
      <li><Image src="/img/test.png" alt="test" /></li>
      <li><Image src="/img/test.png" alt="test" /></li>
      <li><Image src="/img/test.png" alt="test" /></li>
    </ListsGrid>
  </Container>
</template>
