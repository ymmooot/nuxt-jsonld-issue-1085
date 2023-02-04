<template>
  <Tutorial />
</template>

<script>
export default {
  jsonld() {
    return {
      "@context": "https://schema.org",
      "@type": "Product",
      name: "product name",
    };
  },
};
</script>