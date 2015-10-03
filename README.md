To open up our application once you have downloaded or cloned the repository just open the index.html located in the Web-Optimizations directory.
From there you can navigate to any of the other pages located within the repository. If you would prefer not to download or clone the repository
this link will take you directly to the main page. http://tmurph850.github.io/Project-4/

Located within views/js/main.js and starting with line 520 I went in and changed the old function that updates the position of the pizzas
in the background. I removed the repeating variable out of the assignment loop so it would stop causing a forced synchronous layout. At line 545
I reduced the number of pizzas created by the function. Around line 452 I changed the function (changePizzaSizes) so that it would no longer access
the offsetWidth property and no longer cause FS layout.

I also added a few css properties to the .mover class inside of views/css/style.css, these styles help reduce paint cost.