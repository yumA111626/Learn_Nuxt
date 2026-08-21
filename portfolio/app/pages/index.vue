<template>
    <div>
        Hello welcome page
    </div>
</template>

<script setup>
useSeoMeta({
    title: 'Main page',
    description: 'This is Main Page',
    ogTitle: '[og:title]',
    ogDescription: '[og:description]',
    ogImage: '[og:image]',
    ogUrl: '[og:url]',
    twitterTitle: '[twitter:title]',
    twitterDescription: '[twitter:description]',
    twitterImage: '[twitter:image]',
    twitterCard: 'summary'
})

useHead({
    htmlAttrs: {
    lang: 'en'
    },
    link: [
    {
        rel: 'icon',
        type: 'image/png',
        href: '/favicon.png'
    }
    ]
})
</script>