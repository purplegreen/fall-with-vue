    <template>
  <div class="thisbox">
    <h1>{{ msg }}</h1>
    <p>
      more info at:
      <a href="https://dehlix.com" target="_blank" rel="noopener"
        >dehlix.com</a>.
    </p>    
    <h3>Eco</h3>
    <ul>
      <li>
       one
      </li>
      <li>
       two
      </li>
      <li>
        three
      </li>
      <li>
       four
      </li>
      <li>
        five
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Shot",
  props: {
    msg: String,
    content: []
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.thisbox {
  display: flex;
  flex-direction: column;

  width: 38vw;
  background-color: beige;
  padding: 12px;
  margin-top: 10px;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  font-size: 0.9em;
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
