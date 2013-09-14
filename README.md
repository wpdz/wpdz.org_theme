wpdz.org_theme
==============

Theme de wpdz.org

* Le theme utilise [de twitter bootstrap](http://getbootstrap.com/2.3.2/), pour assurer qu'il soit responsive et sur des bases solides.

* Twitter Bootstrap est personalisé et on évite de mettre des classes codées en dur dans le structure HTML par exemple `<div class="span8">bla blas </div>` n'est pas accepté,vous pouvez voir cet [article](http://ruby.bvision.com/blog/please-stop-embedding-bootstrap-classes-in-your-html) pour en savoir plus à la place il faut utilisé [LESSCss](http://lesscss.org/) et sa puissance dans les mixins, dans ce cas notre example devient:
`article{
	.span(8);
}`


* Basé sur un starter theme [underscore](http://underscores.me/) connus aussi par son utilisation des themes WordPress comme twentythirtheen, il est développé par les gens de [Automattic](http://underscores.me/) précisement [themeshaper](http://themeshaper.com/)