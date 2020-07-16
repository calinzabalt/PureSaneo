<script>
let bgImage = "header.jpg";
</script>
<style>
#header {
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}
#header h1{
	text-align:center;
	color: #ffffff;
	font-size: 68px;
	padding: 400px;
}

#First_Section p{
	text-align: center;
	max-width: 900px;
	margin-left: auto;
	margin-right: auto;
	font-size: 18px;
}
#Second_Section .container{
	max-width: 1300px;
	margin-left: auto;
	margin-right: auto;
	letter-spacing: -7px;
}

#Second_Section .container .item{
	width: 50%;
	display: inline-block;
	text-align: center;
	letter-spacing: normal;
}

#Second_Section .container .item img{
	height: 600px;
  max-width: 100%;
}

#Second_Section .container .item img:hover{
box-sizing: border-box;
box-shadow: 0px 7px 45px rgba(0, 0, 0, 0.12);
}



input[type="text"],
  textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    margin-top: 6px;
    margin-bottom: 16px;
    resize: vertical;
  }
  input[type="submit"] {
    background-color: #4caf50;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }
  input[type="submit"]:hover {
    background-color: #45a049;
  }
#Third_Section .container {
    border-radius: 5px;
    max-width: 800px;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
	margin-top: 100px;
  }
  

@media only screen and (max-width: 765px){
	#header h1{
		padding: 100px 10px 100px 10px;
		font-size: 38px;
	}
  #Second_Section .container .item{
    width: 100%;
    padding: 20px 0 20px 0;
  }
  #Second_Section .container .item img{
  box-sizing: border-box;
  box-shadow: 0px 7px 45px rgba(0, 0, 0, 0.12);
  width: 100%;
  }
  #First_Section p{
	font-size: 16px;
  padding: 0 20px 0 20px;
}
}

@media only screen and (max-width: 493px){
	#header h1{
		font-size: 28px;
	}
}

</style>

<svelte:head>
	<title>PureSaneo</title>
</svelte:head>

<section id="header" style="background-image: url('{bgImage}')">
<h1>Wash your hands <br> and feel "safe"</h1>
</section>
<section id="First_Section">
<p>Developed and manufactured by ARSAT,
a trusted and certified quality European aerospace factory
where safety and high quality are fundamentally
required by global brands as our clients, the Astreea®
pedal hand sanitizer is proudly following these standards.
Entirely made from medical stainless steel,
durable, weather resistant and fully mechanical,
Astreea® is the solution for heavy duty intense use.

Quality and value for money rarely meet.
The Astreea® hand sanitizer is one
of these exceptions.</p>
</section>

<section id="Second_Section">
<div class="container">
	<div class="item"><img alt="dispenser" src="1.jpeg"/></div>
	<div class="item"><img alt="dispenser" src="3.jpeg"/></div>
</div>
</section>

<section id="Third_Section">
<div class="container">
<form action="" method="POST">
    <label for="fname">Name</label>
    <input type="text" id="name" name="name" placeholder="Your name.." />

    <label for="lname">Email</label>
    <input
      type="text"
      id="email"
      name="_replyto"
      placeholder="Email address.." />

	<label for="fname">Phone number</label>
    <input type="text" id="name" name="name" placeholder="Phone number.." />

	<label for="fname">Company or Organization</label>
    <input type="text" id="name" name="name" placeholder="Company name .." />  

    <label for="subject">Message:</label>
    <textarea
      id="subject"
      name="subject"
      placeholder="Your message.."
      style="height:200px" />

    <input type="submit" value="Submit" />
  </form>
  </div>
</section>
<br/>
<section id="Four_Section">More Information / Delivery Methods / How is fabricated</section>
<section id="Fifth_Section">
Contact <br/>
- We are on social media <br/>
- If you need support just press this button and write your concers in the box that will appear in the right corner.
</section>

<div class="footer">Footer</div>
