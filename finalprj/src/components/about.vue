<template>
    <div class="about">
        <br><br>
        <h1><b>{{ title }}</b></h1>
        <h2>We Are A Team Of Japan Enthusiats</h2>
		<table style="width: 100%; margin-left: auto; margin-right: auto;margin-top: 2%;">
			<tr>
			<td style="width: 45%;"><img src="@/assets/about.jpg" style="width: 100%; padding-left: 30%;"></td>
			<td style="width: 55%; font-size: 140%; padding-right: 10%;"><p style="max-width: 100%; line-height: 1.6;
  			padding: 1%;
  			margin: 5%;
  			position: relative;
  			text-align: justify;
  			color: black;
  			border-spacing: 10px;">
            Our team is made up of Japan enthusiasts, who have lived and worked in Japan and have a deep appreciation for the country's culture and people. <br> <br>

We aim in providing accurate and up-to-date information about Japan, promoting cultural exchange, or fostering understanding between Japan and other countries. <br><br>
Our mission is to promote greater understanding and appreciation of Japan through informative and engaging content. We believe that by sharing our insights and experiences, we can help others deepen their connection to Japan and its people. <br> <br> 
We aim to provide a wide range of content that appeals to anyone with an interest in Japan. This includes articles on Japanese culture and traditions, reviews of Japanese products and services, interviews with Japanese experts, and updates on the latest news and trends in Japan. <br></p>
  </td>
		</tr>
		</table>
    </div>
</template>

<script>
export default{
    name: 'about',
    data (){
        return{
            title: 'About'
        }
    }
}
</script>

<style scoped>
</style>