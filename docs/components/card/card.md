<script setup>
import CardDefaultExample from './examples/CardDefaultExample.vue'
import CardImageExample from './examples/CardImageExample.vue'
import CardHorizontalExample from './examples/CardHorizontalExample.vue'
</script>
# Vue Card Components - Flowbite

#### Get started with a large variety of Tailwind CSS card examples for your web project

---

:::tip
Original reference: [https://flowbite.com/docs/components/card/](https://flowbite.com/docs/components/card/)
:::

Use these responsive card components to show data entries and information to your users in multiple forms and contexts such as for your blog, application, user profiles, and more.

## Prop - default

<CardDefaultExample />

```vue
<script setup>
import { TheCard } from 'flowbite-vue'
</script>
<template>
  <the-card href="#"/>
</template>
```

## Prop - image

<CardImageExample />

```vue
<script setup>
import { TheCard } from 'flowbite-vue'
</script>
<template>
  <the-card 
    variant="image" 
    href="#" 
    img-src="./images/blog/image-1.jpg" 
    img-alt="Image"
  />
</template>
```

## Prop - horizontal

<CardHorizontalExample />

```vue
<script setup>
import { TheCard } from 'flowbite-vue'
</script>
<template>
  <the-card 
    variant="horizontal" 
    href="#" 
    img-src="./images/blog/image-4.jpg" 
    img-alt="Image"
  />
</template>
```
