# Candy
A theme for Hexo based on [Light](https://github.com/tommy351/hexo-theme-light).

[Demo](http://initrc.github.io/).

# Iconize
There's no navbar in Candy. Instead it shows nav icons so that it aligns with social icons in a single line.

For example, if you have two menus in the navbar, you should be able to see two icons next to social icons, if css and images are provided.

```yml
menu:
  Home: /
  Reading: /reading
```

Candy comes with a reading icon. It lowercases the string `Reading` in `_config.yml` and names the css class name and image with it.

For simplicity, Candy does not include a home icon. The title takes you home.

# Changelog
## 0.2.0
1. Remove the sidebar
2. Remove the navbar and show nav icons next to social icons
3. Center the title and subtitle
4. Show article tag and category in index
5. Add a reading icon

## 0.1.0
1. Change the link color to greenish cyan `#4bc4af`
2. Add social icons to the header
3. Add a 500px icon
