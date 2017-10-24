# django-cms-heroku-template
It is a template for deploy django cms version 3.4.5 to heroku. 

A simple template to launch djangocms in heroku.

Attention to
<ul>
<li>requirements.txt</li>
<li>procfile</li>
<li>static/.keep</li>
<li>project/static/.keep</li>
<li>commits messages</li>
</ul>
both .keep files are to prevent error when executing the command "collectstatic" since you will not find anything.
Once there are files in the "static" directories you can remove them.

I did everything from ubuntu.

I hope it helps.


------------------------------------------------------------------------------------------------------

<h2>Español</h2>

Atención a
<ul>
<li>requirements.txt</li>
<li>procfile</li>
<li>static/.keep</li>
<li>project/static/.keep</li>
<li>mensajes de los commits</li>
</ul>
ambos archivos .keep son para prevenir el error al ejecutar el comando "collectstatic" ya que no encontrará nada. 
Una vez existan archivos en los directorios "static" podrás desaserte de ellos. 

lo hice todo desde ubuntu. 

espero que les ayude.

----------------------------------------------------------------------------
<h3>Links de ayuda</h3>
<ul>
  <li>https://devcenter.heroku.com/articles/deploying-python</li>
  <li>https://github.com/kencochrane/django-cms-heroku  outdated</li>
</ul>
