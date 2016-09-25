# Search
The search function appears as a magnifying glass at the top left of the UI. Clicking on it toggles the module, which animates a text input to its right, where the [user]() can input terms.

On the left most side of the app, when the search is engaged, different intuitive parameters are included. Some are recurring, others are specific to the opened native app (the one in the main view). The parameters combined with the entries supplied by the user will allow the app content to be morphed to the search query based on info pulled from our database!

**[Circles](https://github.com/HaramG/ms/blob/master/Native/circles/circles)**
-
When Search is open, special behaviour is injected into the circles app. By default, the user's last circles search query is supplied. With an empty field supplied and clean params, the hottest circles, by tier, get displayed in their own tier 1/3, 2/3, 3/3 with the middle representing the whole -- see Congregation lower --

Remember circles have their own showcased thoughts, which can be pages (like their created profile), which get opened in the [browser]() as a new tab or even [bookmarked]().

Users can change the scope of the input with the following options:
- Search by title/circle name
- Search by [ID](), which is faster if you know the circle's first digits | *Chosen by circle at birth*
- Search by [tags]() associated with resulted circles

Users can toggle other settings that affect how the results are displayed. 

Users can choose the amount of results to return, which has an impact on how fast the search can be completed. This is also a unique setting, which means it stands independently of other settings like the following ones.

They can keep the tiers or specify a tier they wish to dig deeper into (individuals OR groups OR communities OR 3-way). Depending on the selected setting, the sub-circles are displayed based on different algorithms.

The center result is the closest match based on your specified search settings/parameters. Every added layer of circles around that center point is a prediction or possible outcome based on the selected settings and parameters. Ultimately, the user will be able to customize his own preferences and save those for every layer, meaning you can dim the outermost layers, only display picture on center + layers 1 to 3, etc. Finally clicking on the center circle or one of the converging circles bring this circle to the center and displays important info in a square around it. Outside the square, related circles with ties to the selected circle are displayed.

- **[Individuals]()**:  For this case, it will sort these individuals by layer, where the first layer focuses on loved individuals who have loved other individuals who have loved the resulting individual who has loved them back. Every next layer removes one of those quirks from the equation to finally only return a layer of people who have loved this individual without having been loved back. We call that rejection;
- **[Groups]()**: For groups, there's one circular layer where all the members are displayed in stairwell fashion. The outer layer is composed of an agglomeration of thoughts associated to that group. Inside the square the user can control how the outer layer thoughts are displayed, similar to the search function this one sorts them in the prefered way;
- **[Communities]()**: For communities, the same center piece is present. On the edges of the screen are floated the varying groups that compose this community. Every group, of course, has its set of members which are displayed on the interior angle pointing towards the center. The area between the groups and the center piece is composed of thoughts associated with that community, which of course, again, can be sorted;
- **[Congregation]()**: This one is special, there's only one of them. It can be accessed by having a blank search query where all three tiers are chosen for display. Clicking on it pops over a menu where circles that have earned gold chips are displayed. The congregation's profile page is programmatically created and updates automatically. It holds important information like the global feed of public thoughts, site-wide updates performed by the developers -> which will be replaced by a selfless voting and implementation system based on [user]() trust.

Bundled settings (choose one):
- Users can choose to sort from goldest to coldest;
- Users can choose to sort from most popular to least popular (views);
- Users can choose to sort from physical location, closest to farthest;
- Users can choose to sort from closest-related.

**[Exchange](https://github.com/HaramG/ms/blob/master/Native/exchange/exchange)**
-
Functions very similarly, at least visually and mentally, to the circle searching adventure. The interface, however, doesn't rely as heavily on thought directives and elements, comparatively.


**[Creator](https://github.com/HaramG/ms/blob/master/Native/creator/creator)**
-
s

**[The Game](https://github.com/HaramG/ms/blob/master/Native/the-game/game)**
-
s

**[Market](https://github.com/HaramG/ms/blob/master/Native/browser/browser)**
-
s

