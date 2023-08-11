<template>
    <div class="info-card-presentational large inline flex vertical bg-default corner outline text-center left">
        <i :class="`f1 circle large default disabled ${ iconClass }`"></i>
        <div class="f4 text-bold">{{ headerText }}</div>
        <p>{{ descriptionText }}</p>
    </div>
</template>

<script>
export default {
    name: 'InfoCardPresentational',
    props: {
      iconClass: String,
      headerText: String,
      descriptionText: String
    },
};
</script>
