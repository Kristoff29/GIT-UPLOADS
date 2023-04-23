<template>
  <div class="hello">
    <br>
    <h1>{{ msg }}</h1>
    <h2>The Land Of The Rising Sun</h2>
		<table style="width: 100%; margin-left: auto; margin-right: auto;margin-top: 2%;">
			<tr>
			<td style="width: 45%;"><img src="@/assets/background.jpg" style="width: 100%; padding-left: 30%;"></td>
			<td style="width: 55%; font-size: 140%; padding-right: 10%;"><p style="max-width: 100%; line-height: 1.6;
  			padding: 1%;
  			margin: 5%;
  			position: relative;
  			text-align: justify;
  			color: black;
  			border-spacing: 10px;">Japan is a fascinating country that has so much to offer, from its rich history and culture to its mouth-watering cuisine and stunning landscapes. Whether you're a first-time visitor or a seasoned traveler, Japan has something for everyone.

One of the first things you'll notice when you arrive in Japan is the warm welcome you'll receive from the locals. Japanese people are known for their hospitality and their dedication to providing excellent customer service. From the moment you step off the plane, you'll be greeted with a smile and a bow, and you'll feel right at home.

As you explore Japan, you'll discover a wealth of cultural treasures, from ancient temples and shrines to modern art museums and galleries. Tokyo, the capital city, is a hub of activity, with a dizzying array of sights, sounds, and experiences to enjoy. From the famous Shibuya Crossing to the tranquil gardens of the Imperial Palace, Tokyo is a city that never sleeps.</p>
  </td>
		</tr>
		</table>

    
	</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Japan'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

h3 {
  color: black;
			font-size: 24px;
			font-weight: bold;
			font-family: Arial, sans-serif;
			text-align: center;
			margin-top: 50px;
      margin-left: 50px;
      margin-right: 50px;
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

.hello {
  background-color: white;
}
</style>
