# Sansan-OSINT
All about infosec related stuff at our _"prestigious"_ university: Universidad Técnica Federico Santa María.

From ownages and defacements of local servers that haven't been disclosed or breaches that remain in the dark to insecure configs that **shouldn't** exist in the first place somewhere at our campus, 
this is your place for info about events happening at our uni that aren't being properly reported nor covered.


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

 _(currently accepting submissions and tips for future research)_
