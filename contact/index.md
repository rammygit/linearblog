---
title: Linear
layout: default
---
<div id="main">
		<div class="container">
			<div class="row">
				<form action="//formspree.io/rammysmailbox@gmail.com" method="POST">
					 <fieldset>
					 <label for="name">Your name</label><br>
					 <input type="text" name="name" placeholder="Name" required>
					 </fieldset>
					 <fieldset>
					 <label for="_replyto">Your email</label><br>
					 <input type="email" name="_replyto" placeholder="example@domain.com" required>
					 </fieldset>
					 <fieldset>
					 <label for="message">Your message</label><br>
					 <textarea name="message" rows="1" placeholder="Message" required></textarea>
					 </fieldset>
					 <input class="hidden" type="text" name="_gotcha" style="display:none">
					 <input type="hidden" name="_subject"  value="Message via http://rammygit.github.io/linearblog">
					 <input type="hidden" name="_next" value="{{ site.baseurl }}/contact" />
					 <input class="button submit" type="submit" value="Send">
				</form>
			</div>
		</div>
	</div>
