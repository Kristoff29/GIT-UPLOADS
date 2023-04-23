<template>
    <div class="contact">
        <br><br>
        <h1>{{ title }}</h1>
        <br>
    <p>Have a question or feedback? <br> We'd love to hear from you! Please fill out the form below and <br> we'll get back to you as soon as possible.</p>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required><br><br>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required><br><br>
      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="4" cols="50" required></textarea><br><br>
      <input type="submit" value="Submit">
    </form>
    </div>
</template>

<script>
export default{
    name: 'contact',
    data (){
        return{
            title: 'Contact Us'
        }
    }
}
</script>

<style scoped>

p {
        text-align: center;
        color: #666;
        margin: 20px 0;
        font-size: 25px;
        color: black;
      }
      form {
        width: 80%;
        max-width: 600px;
        margin: 0 auto;
        background-color: #fff;
        padding: 20px;
        border-radius: 5px;
        box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      }
      label {
        display: block;
        margin-bottom: 10px;
        color: #333;
        font-weight: bold;
      }
      input[type="text"],
      input[type="email"],
      textarea {
        width: 100%;
        padding: 10px;
        border-radius: 3px;
        border: 1px solid #ccc;
        font-size: 16px;
        margin-bottom: 20px;
      }
      textarea {
        height: 150px;
      }
      input[type="submit"] {
        background-color: #f9a826;
        color: #fff;
        border: none;
        padding: 10px 20px;
        border-radius: 3px;
        cursor: pointer;
        transition: background-color 0.3s;
      }
      input[type="submit"]:hover {
        background-color: #d18d26;
      }
      .contact-icon {
        font-size: 20px;
        color: #333;
        margin-right: 5px;
      }
      .contact-text {
        font-size: 16px;
        color: #333;
      }
      .contact-info {
        margin-bottom: 20px;
      }
      .contact-info a {
        color: #333;
      }
      .contact-info a:hover {
        color: #f9a826;
        text-decoration: none;
      }
      .map-container {
        margin-top: 50px;
        position: relative;
        overflow: hidden;
        padding-top: 56.25%;
      }
      .map-container iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border: 0;
      }
      /* Add more complicated styling for the contact form */
      .contact-form {
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 50px;
        position: relative;
        background: url('https://www.w3schools.com/w3images/map.jpg') no-repeat center center fixed;
        background-size: cover;
        padding: 50px;
        min-height: 500px;
      }
</style>