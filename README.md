# Recipes
Collection of recipes I have taken from various sources.

Authors are credited where they are know, where they are not, this field is left blank.

## Index of Recipes
Recipes have been divided into sweet and savoury.

*NB. Links are designed to work through the GitHub pages setup for this Repo ([thomasboxall.github.io/recipes](https://thomasboxall.github.io/recipes)) not through the `README.md` file.*

### Savoury

{% assign doclist = site.pages | sort: 'url'  %}
<ul>
   {% for doc in doclist %}
        {% if doc.name contains '.md' and doc.dir contains 'savoury/' %}
            <li><a href="{{ site.baseurl }}{{ doc.url }}">{{ doc.dir | url_decode | remove: "/savoury/" }}{{ doc.name }}</a></li>
        {% endif %}
    {% endfor %}
</ul>

### Sweet
* [Banoffi Pie](sweet/banoffi-pie)
* [Bread and Butter Pudding](sweet/bread-and-butter-pudding)
* [Chocolate Brownie Cake](sweet/chocolate-brownie-cake)
* [Chocolate Cheesecake](sweet/chocolate-cheesecake)
* [Chocolate and Pistachio Fudge](sweet/chocolate-pistachio-fudge)
* [Chocolate Zucchini Cake](sweet/chocolate-zucchini-cake)
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
* [Yoghurt Cake](sweet/yoghurt-cake)