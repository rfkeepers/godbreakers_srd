<!-- ============================== Script ============================== -->
<script setup>
import Options from '@/components/Options.vue';
</script>

<!-- ============================== Template ============================== -->
<template>
<h1 class="title">
    <b>GOD</b><span class="break"/>BREAKERS
</h1>

You are a tool.  Made to destroy the unbroken god.  Fearsome and powerful they plot to annihilate any who approach, you included.  But that is your goal.  You are a godbreaker.  You have something they do not.  You cannot fail.

<h2>
    In this game:
</h2>
<Options bullet="&#187;" :options="[
    'The players have a single goal: to take down the unbroken god.',
    'The going will be rough.  Not every approach will be successful.  The world will position itself against you.',
    'So long as you keep trying, you will eventually succeed.  That is guaranteed by who you are.  By what you are.',
]" />

<h3>
    Todo:
</h3>
Not in any particular order.
<Options bullet="&#187;" :options="[
    'What is even going on here?',
]" />

<div style="display: none">
    Random notes to myself.

    decide things.

    change all scss color to var

    tokens: 2d6 roll under instability whenever defying danger.  Whenever the player wants, they can make an act of desperation and pay off the MC with tokens.  the MC uses tokens to establish badness.
</div>

</template>

<!-- ============================== Style ============================== -->
<style lang="scss" scoped>
</style>
