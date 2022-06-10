<form action="https://docs.google.com/forms/d/e/1FAIpQLSdoDt3sQmuKod12ocUN5DjcF5kKHuYGTrLGAnTZLyEYFHD4Vg/formResponse" method="POST">
	<div class="fields">
		<div class="field">
			<label for="rsvping">I'm RSVPing for *</label>
			<textarea name="entry.559352220" id="rsvping" rows="2" placeholder="Please include any children in your answer too!"></textarea>
		</div>
		<div class="field">
			<label for="email">Email *</label>
			<input type="text" name="entry.443565211" id="email" placeholder=""/>
		</div>
		<div class="field">
			<label for="qcoming">First things first, are you planning on attending the wedding? *</label>
			<p>
				<input type="radio" id="comingyes" name="entry.994465564" value="Yes">
				<label for="comingyes">Yes</label>
			</p>
			<p>
				<input type="radio" id="comingno" name="entry.994465564" value="No">
				<label for="comingno">No</label>
			</p>
		</div>
		<div class="field">
			<label for="food">Do you have any dietary requirements we should be aware of?</label>
			<input type="text" id="food" name="entry.1751303409"/>
		</div>
		<div class="field">
			<label for="message">Is there anything else we should know?</label>
			<textarea name="entry.1514847841" id="message" rows="4"></textarea>
		</div>
	</div>
	<ul class="actions">
		<li><input type="submit" value="Send response" class="primary" /></li>
	<!--	<li><input type="reset" value="Reset" /></li> -->
	</ul>
</form>
<ul class="icons">

	{% if site.twitter_url %}
				<li><a href="{{ site.twitter_url }}" class="icon fa-twitter" target="_blank"><span class="label">Twitter</span></a></li>
				{% endif %}
				{% if site.googleplus_url %}
				<li><a href="{{ site.googleplus_url }}" class="icon fa-google-plus" target="_blank"><span class="label">Google+</span></a></li>
				{% endif %}
				{% if site.facebook_url %}
				<li><a href="{{ site.facebook_url }}" class="icon fa-facebook" target="_blank"><span class="label">Facebook</span></a></li>
				{% endif %}
				{% if site.instagram_url %}
				<li><a href="{{ site.instagram_url }}" class="icon fa-instagram" target="_blank"><span class="label">Instagram</span></a></li>
				{% endif %}
				{% if site.pinterest_url %}
				<li><a href="{{ site.pinterest_url }}" class="icon fa-pinterest" target="_blank"><span class="label">Pinterest</span></a></li>
				{% endif %}
				{% if site.gitlab_url %}
				<li><a href="{{ site.gitlab_url }}" class="icon fa-gitlab" target="_blank"><span class="label">GitLab</span></a></li>
				{% endif %}
				{% if site.github_url %}
				<li><a href="{{ site.github_url }}" class="icon fa-github" target="_blank"><span class="label">GitHub</span></a></li>
				{% endif %}
				{% if site.slack_url %}
				<li><a href="{{ site.slack_url }}" class="icon fa-slack" target="_blank"><span class="label">Slack</span></a></li>
				{% endif %}
				{% if site.linkedin_url %}
				<li><a href="{{ site.linkedin_url }}" class="icon fa-linkedin" target="_blank"><span class="label">LinkedIn</span></a></li>
				{% endif %}

</ul>
