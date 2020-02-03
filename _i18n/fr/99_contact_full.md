<form action="https://docs.google.com/forms/d/e/1FAIpQLScTwxhZhTH2P7m-alltgd7LccRFVm6DOWTKR49zpxERLth3Pw/formResponse" method="POST">
	<div class="fields">
		<div class="field">
			<label for="rsvping">Je réponds de la part de *</label>
			<textarea name="entry.559352220" id="rsvping" rows="2" placeholder="N'oubliez pas vos enfants !"></textarea>
		</div>
		<div class="field">
			<label for="Adresse mail">Email *</label>
			<input type="text" name="entry.443565211" id="email" placeholder=""/>
		</div>
		<div class="field">
			<label for="qcoming">Tout d'abord, pouvez-vous venir à notre mariage ? *</label>
			<p>
				<input type="radio" id="comingyes" name="entry.994465564" value="Yes">
				<label for="comingyes">Oui</label>
			</p>
			<p>
				<input type="radio" id="comingno" name="entry.994465564" value="No">
				<label for="comingno">Non</label>
			</p>
		</div>
		<div class="field">
			<label for="qeve">Restez-vous pour la soirée ? On estime la quantité de nourriture nécessaire pour la soirée, donc pas de problème si vous changez d'avis. *</label>
			<p>
				<input type="radio" id="eveyes" name="entry.934821120" value="Yes">
				<label for="eveyes">Yes</label>
			</p>
			<p>
				<input type="radio" id="eveno" name="entry.934821120" value="No">
				<label for="eveno">No</label>
			</p>
		</div>
		<div class="field">
			<label for="food">Avez-vous une allérgie ou une intolérance alimentaire dont il faut qu'on soit au courant ?</label>
			<input type="text" id="food" name="entry.1751303409"/>
		</div>
		<div class="field">
			<label for="qcoming">Comment pensez-vous faire le trajet ?</label>
			<p>
				<input type="radio" id="travelcar" name="entry.1804390083" value="Car">
				<label for="travelcar">En voiture</label>
			</p>
			<p>
				<input type="radio" id="travelpublic" name="entry.1804390083" value="Public transport">
				<label for="travelpublic">En transport en commun</label>
			</p>
		</div>
		<div class="field">
			<label for="qcoming">Est-ce que ça vous intéresserait qu'on vous mette en contact avec d'autres personnes pour organiser une covoiturage (ou pour partager un taxi) ?</label>
			<p>
				<input type="radio" id="contravelyes" name="entry.936402010" value="Yes">
				<label for="contravelyes">Oui</label>
			</p>
			<p>
				<input type="radio" id="contravelno" name="entry.936402010" value="No">
				<label for="contravelno">Non</label>
			</p>
		</div>
		<div class="field">
			<label for="wherefrom">Le cas échéant, vous voyagez d'où ?</label>
			<input type="text" name="entry.85772937" id="wherefrom" placeholder=""/>
		</div>
		<br>
		<div class="field">
			<label for="message">Autre chose à nous dire ?</label>
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
