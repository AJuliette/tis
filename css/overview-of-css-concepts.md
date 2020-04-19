# Overview of CSS concepts

[Source: Tania Rascia Blog](https://www.taniarascia.com/overview-of-css-concepts/)

I now know for sure that all my strugglings from CSS is that I never tried to look things up.

I'm eventually doing it, one tutorial at a time, but if you want to make one big progress you can read the article above.

What I (personnally) retain from this article:
  - [box model](https://www.taniarascia.com/overview-of-css-concepts/#box-model): have you ever suffered from subtles non-alignment in a navbar ? I did. And if I knew `box-sizing: border-box;` at the time, all my suffering would have gone away ;
  - [shorthand properties](https://www.taniarascia.com/overview-of-css-concepts/#shorthand-properties): do I still dutifully write CSS like that:
```css
div {
  padding-top: 15px;
  padding-right: 5px;
  padding-bottom: 10px;
  padding-left: 5px;
}
```
You bet I do ! Because I did not even try to learn the "one-liner", turns out the values are applied clockwise from top to left, so the above would look like: 
```css
div {
  padding: 15px 5px 10px 5px;
}

To finish: take time to dive in Tania Rascia's posts, they're great !