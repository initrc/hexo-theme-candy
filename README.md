# Candy
A theme for Hexo based on [Light](https://github.com/tommy351/hexo-theme-light).

[Demo](http://initrc.github.io/).

# Iconize
There's no navbar in Candy. Instead it shows nav icons so that it aligns with social icons in a single line.

For example, if you have two menus in the navbar, you should be able to see two icons next to social icons, if css and images are provided.

``` yml themes/candy/_config.yml
menu:
  Home: /
  Reading: /reading
```

Candy comes with a reading icon. It lowercases the string `Reading` in `_config.yml` and use that as the css class name and image name. You can follow this pattern and extend.

Candy does not include a home icon for simplicity. The title takes you home.

# Changes
1. Change the link color to greenish cyan `#4bc4af`
2. Remove the side bar
3. Add social icons to the header
4. Remove the navbar and show nav icons next to social icons
5. Center the title and subtitle
6. Show article tag and category in index
7. Add a 500px icon
8. Add a reading icon
