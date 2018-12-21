<template>
  <div>
    <h1>{{ question }}</h1>
    <h4> You can choose {{limit}} options</h4>
    
     <md-list>
      <md-subheader>Notifications</md-subheader>

      <md-list-item>
        <md-checkbox v-model="voteLanguage" value="javascript" />
        <span class="md-list-item-text">JavaScript</span>
      </md-list-item>

      <md-list-item>
        <md-checkbox v-model="voteLanguage" value="java" />
        <span class="md-list-item-text">Java</span>
      </md-list-item>
     </md-list>

    <div>       <md-button class="md-primary">NEXT</md-button>
</div>
  </div>
</template>

<script>

export default {
  name: 'HelloWorld',
   data: () => ({
      voteLanguage: ['javascript']
    }),
  props: {
    question: String,
    limit: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}

li {
  font-size: 20px;
}

li span {
  float: left;
  color: darkmagenta;
}


</style>
