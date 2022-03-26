# wowchemy-publication-awards


Adds an "awards" links to the publication widget for wowchemy/hugo websites. 


Simply add the "layouts" folder within your website's folder (i.e., at the same level as "content" and "config"). 

You can then add awards to your publications, by adding 

```
awards:
- name: "Best paper award"
  url: "http://conference/awards/"
- name: "Double best paper"
  url: ""
```

within the index.md file of your publication. You can have multiple awards per publications. 

The results can be seen on my webpage: https://jroluttringer.github.io/
By default, the new award button is the same color as the DOI,CITE,PDF... buttons, but filled. 

You can slightly change the way the award button looks at line 36 of 'page_links.html' (within the layouts folder). You can switch the button class for any standard bootstrapt button. 

For example, switching "btn-primary" for "btn-warning" will make the button orange, while "btn-success" will make it green. Using "btn-outline-" instead of "btn-" creates a button similar to the standard ones (used for DOI, CITE and so on). For example, changing the class used at line 36 by "btn-outline-success" will make the button awards non-filled and green.
