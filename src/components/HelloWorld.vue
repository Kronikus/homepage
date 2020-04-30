<template>
 <div> <!-- root node -->
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p> <img class="pic" src="../assets/cat.jpeg"> </p>
    <table class="table">
        <th>Video</th>
        <th>Chat</th>
        
        <tr>
        <td><iframe src="https://player.twitch.tv/?channel=l1ve1nthesky" frameborder="0" allowfullscreen="true" scrolling="no" height="378" width="620"></iframe><a href="https://www.twitch.tv/l1ve1nthesky?tt_content=text_link&tt_medium=live_embed" style="padding:2px 0px 4px; display:block; width:345px; font-weight:normal; font-size:10px; text-decoration:underline;">Watch live video from L1ve1nTheSky on www.twitch.tv</a></td>
        <td><iframe src="https://www.twitch.tv/embed/l1ve1nthesky/chat" frameborder="0" scrolling="no" height="500" width="350"></iframe></td>
        </tr>
        <td>Data 3</td>
        
    </table>
  </div>
 </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Under construction'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
