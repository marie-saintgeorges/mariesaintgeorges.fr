---
layout: default
title: ""
description: "Hey, bienvenue ! Je m’appelle Joe, et je vous propose ici de découvrir ou d’approfondir votre connaissance du yoga."
---

{% if site.news %}
<div id="news" class="infobox">
    <p>
      {{ site.news }}
    </p>
</div>
{% endif %}

<div id="home-tiles">
	<div class="infobox" onclick="location.href = '/formations'">
		<h2><span>Formations<br/>sur-mesure</span></h2>
		<p>
			Les formations intra-entreprises ont un premier atout précieux : la cohésion du groupe. Je vous propose de construire ensemble, après un recueil de vos besoins et de vos objectifs une formation sur-mesure (dates - durées - contenu). Nous décidons des objectifs de la formation.
		</p>
	</div>
	<div class="infobox" onclick="location.href = '/etablissements-scolaires'">
		<h2><span>Etablissements scolaires</span></h2>
		<p>La capacité à entrer en soi-même, à se connaître, aide le jeune à prendre de la distance, à
réfléchir, à se concentrer, à écouter. Il doit savoir effectuer ce détour par sa vie intérieure pour
enrichir pleinement sa vie extérieure. Oser ce face-à-face permet de se construire et s’unifier,
et ceci dès le plus jeune âge.</p>
	</div>
	<div class="infobox" onclick="location.href = '/seance-individuelle'">
		<h2><span>Séance individuelle</span><br/>&nbsp;</h2>
		<p>Depuis plus de 10 ans, j’accompagne les enfants, les adolescents et les adultes en séance individuelle.
	C’est prendre le temps de s’intérioriser et de trouver les ressources dont nous disposons pour les réactiver.
	C’est l’occasion d’approfondir la connaissance de soi pour faire face à une épreuve ou un stress.</p>
	</div>
</div>

<div id="me" class="infobox">
	<img src="{{ '/assets/me.jpg' | relative_url }}"/>
	<p>
		<b>Mon public</b> est vaste puisqu'il regroupe aussi bien les entreprises que les établissements scolaires (maternelle, primaire, collège, lycée, étudiants et enseignants). 
		<br/>
		<br/>
		<b>Mes domaines d’expertise</b> comportent deux grands axes : <b>la Connaissance de Soi</b>, dont l’intelligence émotionnelle et  <b>la Communication</b>. Je me base sur la théorie des Intelligences Multiples d'Howard Gardner pour développer plus spécifiquement l'lntelligence Personnelle et l’Intelligence Sociale. C'est apprendre à communiquer avec soi-même pour mieux communiquer avec l’autre.
		<br/>
		<br/>
		J'ai à coeur de <b>permettre à chacun</b> de faire un pas vers la liberté en favorisant la conscience de soi, et en cheminant de l’agitation extérieure à la quiétude intérieure : pour cela nous possédons toutes les ressources nécessaires, à nous à les réactiver. 
		<br/>
		<br/>
		<b>Mes atouts</b> me permettent une adaptivité au milieu d’intervention notamment grâce à une grande créativité. Mon enthousiasme et mon dynamisme sont au service de l’efficacité pour transmettre, partager, contribuer, faire grandir intérieurement.
	</p>
</div>

