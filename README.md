I. Website Performance Optimization portfolio project

II. Index.html – Optimization Tasks

Steps taken:

1- Added CSS Information to Index.html and removed link to style.css file
2- Added async attribute to analytics.js script tag so that it doesn’t block DOM processing 
3- Minified CSS/JS
4- Inline CSS for screen
5- Removed Google Font from index.html added font to CSS on page.
7- Used Kraken to Compressed/optimized images


II.Pizza.html – Optimization tasks (fixed forced sync layout issues)

- Declaring the sine variable,var sine = document.body.scrollTop / 1250 outside of the for loop will prevent it form being created every time the loop is executed(reduced average time to load
last 10 frames from 40ms to 2ms – a 95% decrease in load time)
-Declaring the elem variable outside the loop will prevent it from being created every time the loop is executed(line 529)

-Cached querySelectorAll() and simplified newWidth
calculation in changePizzaSizes(); (reduced time to resize pizzas
from 160ms to 0.5ms – a 99.69% decrease in load time)

-Replaced getElementsByClassName() instead of querySelectorAll() to 
improve performance (reverted - see inline comments - line 441)

- Use screen height to calculate number of pizzas to display rather than 
having it hard coded to 200 pizzas (see inline comments - line 521)


