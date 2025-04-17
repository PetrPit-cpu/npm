<template>
  <div>
    <NuxtPage />
  </div>
</template>
<script setup>
const metaDescription = 'Сервис моментальных выплат для физических лиц.';

const metaTitle = 'Моментальные выплаты';

useHead({
  title: metaTitle,
  meta: [
    {
      name: 'description',
      content: metaDescription,
    },
  ],
  script: [
    {
      innerHTML: `
        (function(m,e,t,r,i,k,a){
          m[i]=m[i]||function(){(m[i].a=m[i].a||[]).push(arguments)};
          m[i].l=1*new Date();
          for (var j = 0; j < document.scripts.length; j++) {
            if (document.scripts[j].src === r) { return; }
          }
          k=e.createElement(t),a=e.getElementsByTagName(t)[0],
          k.async=1,k.src=r,a.parentNode.insertBefore(k,a)
        })
        (window, document, "script", "https://mc.yandex.ru/metrika/tag.js", "ym");

        ym(99517597, "init", {
          clickmap:true,
          trackLinks:true,
          accurateTrackBounce:true
        });
      `,
      type: 'text/javascript',
    },
  ],
  noscript: [
    {
      innerHTML: `
        <div><img src="https://mc.yandex.ru/watch/99517597" style="position:absolute; left:-9999px;" alt="" /></div>
      `,
    },
  ],
});
</script>
