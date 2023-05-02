# Recipes
Collection of recipes I have taken from various sources.

Authors are credited where they are know, where they are not, this field is left blank.

## Index of Recipes
Recipes have been divided into sweet and savoury.

*NB. Links are designed to work through the GitHub pages setup for this Repo ([thomasboxall.github.io/recipes](https://thomasboxall.github.io/recipes)) not through the `README.md` file.*

### Savoury
<!-- * [Bolognese Sauce](savoury/bolognese)
* [Chicken & Chorizo Jambalaya](savoury/chicken-chorizo-jambalaya)
* [Chicken with Honey and Soy sauce](savoury/chicken-honey-soy)
* [Chicken & Mushroom pie](savoury/chicken-mushroom-pie)
* [Chicken Satay](savoury/chicken-satay)
* [Cod & Prawn fishcakes](savoury/cod-prawn-fishcakes)
* [Cornish Pasty](savoury/cornish-pasty)
* [Curry Sauce](savoury/curry-sauce)
* [Garlic Broccoli](savoury/garlic-broccoli)
* [Hunters Chicken](savoury/hunters-chicken)
* [Macaroni & Cheese](savoury/macaroni-cheese)
* [Mongolian Beef](savoury/mongolian-beef)
* [Quiche Lorraine](savoury/quiche-lorraine)
* [Savoury Rice](savoury/savoury-rice)
* [Shortcrust Pastry](savoury/shortcrust-pastry)
* [Simple Pizza dough](savoury/simple-pizza)
* [Slow Cooker Ribs](savoury/slow-cooker-ribs)
* [Swedish Meatballs with Cream Sauce](savoury/swedish-meatballs-with-cream-sauce)
* [Tandoori Chicken](savoury/tandoori-chicken)
* [Thai Green Curry](savoury/thai-green-curry)
* [Three Cheese Macaroni](savoury/three-cheese-macaroni)
* [Tomato Sauce](savoury/tomato-sauce)
* [Vegetable Samosas](savoury/vegetable-samosa) -->

{% assign doclist = site.pages | sort: 'url'  %}
<ul>
{% for doc in doclist %}
{% if doc.name contains '.md' and doc.dir contains 'savoury/' %}
<li><a href="{{ site.baseurl }}{{ doc.url }}">{{ doc.dir | url_decode | remove: "/savoury/" | remove: ".md" }}{{ doc.name }}</a></li>
{% endif %}
{% endfor %}
</ul>

### Sweet
<!-- * [Banoffi Pie](sweet/banoffi-pie)
* [Bread and Butter Pudding](sweet/bread-and-butter-pudding)
* [Chocolate Brownie Cake](sweet/chocolate-brownie-cake)
* [Chocolate Cheesecake](sweet/chocolate-cheesecake)
* [Chocolate and Pistachio Fudge](sweet/chocolate-pistachio-fudge)
* [Chocolate Zucchini Cake](sweet/chocolate-zucchini-cake)
* [Cinnamon Bun Bites](sweet/cinnamon-bun-bites)
* [Flapjacks](sweet/flapjacks)
* [Ice Cream (Simple)](sweet/ice-cream-simple)
* [Lemon Curd](sweet/lemon-curd)
* [Marmalade Cake](sweet/marmalade-cake)
* [Mocha Mousse](sweet/mocha-mousse)
* [Profiteroles](sweet/profiteroles)
* [Pumpkin Pie](sweet/pumpkin-pie)
* [Sticky Toffee Pudding](sweet/sticky-toffee-pudding)
* [Treacle Tart](sweet/treacle-tart)
* [Waffles](sweet/waffles)
* [White Mice Graveyard](sweet/white-mice-graveyard)
* [Yoghurt Cake](sweet/yoghurt-cake) -->
{% assign doclist = site.pages | sort: 'url'  %}
<ul>
{% for doc in doclist %}
{% if doc.name contains '.md' and doc.dir contains 'sweet/' %}
<li><a href="{{ site.baseurl }}{{ doc.url }}">{{ doc.dir | url_decode | remove: "/sweet/" | remove: ".md" }}{{ doc.name }}</a></li>
{% endif %}
{% endfor %}
</ul>