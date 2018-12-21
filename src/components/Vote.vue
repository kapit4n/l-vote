<template>
  <div>
    <h1>{{ question }}</h1>
    <h4> You can choose {{limit}} options</h4>
    <ul>
    <li>
     <input type="checkbox"> 
     <span>Javascript</span>
    </li>
    
    <li>
     <input type="checkbox"> 
     <span>Java</span>
    </li>
    
    <li>
      <input type="checkbox"> 
      <span> Scala </span>
    </li>
    </ul>
    <div> <button> NEXT </button></div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
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

li input {
  float: left;
}

</style>
