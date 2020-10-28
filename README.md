<!DOCTYPE html>
<html>
	<head>
		<title>Inline Styles</title>
		<link rel="stylesheet" type="text/css" href="style/style.css"> 
	</head>
	<body>
		<div class="head">
			&#9675 &#9675 &#9675
		</div>
		
		<div class="body">
			<div class="title">
				<h1>HTML Form</h1>
				<p>Sign up to the newsletter from below to receive the latest news from our company.</p>
			</div>
			<div class="content">
				<form>
					<div class="email-form">
						<label for="email" ><h4>Email</h4></label>
						<input id="email" type="email" name="email" placeholder="hello@contact.com">
						<p>We will send you an email describing how to activate your newsletter subscription.</p>
					</div>
					
					<div class="name-form">
						<label for="first-name"><h4>Name</h4></label>
						<div class="name-insert">
							<input id="first-name" name="first-name" placeholder="First">
							<input name="last-name" placeholder="Last">
						</div>
					</div>
					
					<div class="format-form">
						<h4>Preferred newsletter format</h4>
						<input type="radio" name="format" id="text" value="text">
						<label for="text">Text</label></br>
						<input type="radio" name="format" id="html" value="html">
						<label for="html">HTML</label>
					</div>
					
					<hr>
					
					<div class="end-form">
						<input type="submit" id="submit" value="Submit">
						<span>or <input id="reset" type="reset" value="Clear and start from scratch"></span>
					</div>
				</form>
			</div> 
		</div>
	</body>
</html>
