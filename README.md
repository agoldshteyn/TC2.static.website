## Usage
The website can be viewed locally by pulling all of the files in the git
repository, running the command "jekyll serve" in the command prompt, and
typing in "http://localhost:4000/TC2.static.website/" into your browser,
which will bring you to the home page.

The website can also be viewed by using GitHub Pages through the following
link: https://agoldshteyn.github.io/TC2.static.website/

## Design Decisions
The fictional character, Jane Artamova, for whom this website has been built
is an author of books and short stories that explore the relationship between
humans and nature as well as touch upon the ways in which experiences impact
our behavior. Since this author mainly covers nature related topics, the base
color for her website was made to be green. The Comfortaa font was used throughout
the website because it has clear and smooth edges, reflecting the lyricism and
preciseness of the words that Artamova uses in her pieces.

In the header, Artamova's name is front and center to draw the user's foveal
vision to her name. Then, there is a navigation bar in between two horizontal
lines, which are meant to suggest that the words in between them are clickable.
In order to further hint at this, when the user hovers their cursor on a
word, that word becomes underlined, suggesting that it is a link or an option,
prompting the user to click it. In an effort to communicate which page the user
is on once they clicked on a word in the navigation bar, the word associated
with the active page turns green.

Although the navigation bar contains many clickable page options, the layout for
only "Published Work" and "Writing Workshops" pages has been made. Since the eye rarely looks to the left (via natural gaze patterns), all text and images were centered. A grid was used to convey books, short stories, and workshops that
the author either wrote or held. This grid was made to be compact (not spanning
the entire page left to right) in order to allow the user to focus on the
content by reading up and down and to promote a feeling of order. On each page,
the height and width of each grid is the same in order to support this feeling
of being organized. The main headers and sub headers have a larger size than
compared to words in the nav bar and their size indicates what section the
user is in. In other words, the larger headers indicate a new section and the
smaller headers indicate that there is a new section within the current section.
There is a break between the headers and grid of images to give the user the
ability to break up the images and text and to understand what section each
image belongs to. In the "Writing Workshops" page, the grids were created a
little differently. Each grid here consists of an image on the left to quickly
indicate what a workshop might be about and then a description of the
workshop on the left, aligned to the left. The grids here are compact and
contain a slightly green background to give the user the feeling of order,
to clearly separate the events, and draw the user's foveal vision to each event
via the slightly green background color. The text is aligned left due to
the user's F-patterns.

The design of this website matches Artamova's writing with its organized
layout and green color scheme. It also allows the user to quickly and easily
differentiate between Artamova's published works or workshops, giving them
a pleasant experience that they might associate with Artamova herself.

## Challenge
Since I am new to making websites, this assignment as a whole was challenging.
I focused on challenging myself specifically by creating a grid, making a
navigation bar that changed based on where the user was and how they were
interacting with it, and generating code that was relatively automated.

I succeeded in making a grid in both of my layouts, one that included only
images and another that included an image and text to it. In an effort to make
this process automated, I made a collection for every set of images/text that
I needed to use a grid for and then made a for loop in my html layout file.
By doing this, the grids I have made will automatically generate new spaces if
I need to add new images or text. By trying to make grids, I also developed a
better idea of how to use "div" when grouping items together, along with lists,
and liquid matter. That said, I got caught up in developing these grids that I
did not have enough time to figure out how to make them change size when making
the page window smaller. As a result, when the page window is relatively small,
the grids step out of their usual position and overlap with the outer green
background. I also wanted to include a link on below each book and
short story so that when the user clicked on it, they would be routed to Amazon
to buy that book or short story, but I did not have enough time to implement this.

The navigation bar I created is more interactive. When the user hovers over a
word, it becomes underlined and when they click a word, it changes color from grey
to green to indicate that the user is on that particular page. It was while
making this navigation bar that I understood how to use liquid matter and also
had to figure out how to re-order the pages to my liking.

Throughout this process, I developed a much better understanding of how
jekyll works, how all of the files needed to create a website link together,
and useful techniques to create different types of layouts.

## Credits
I used the following website as inspiration: https://roniloren.com/

As I was coding, I frequently looked at Stack Exchange and w3schools in
order to learn how to implement different aspects of my design.

I used the following images for books and short stories, which are works that
real authors have published. I am using these as proxies for fictional works
that Jane Artamova might have written.

Books:
https://images-na.ssl-images-amazon.com/images/I/41HH0qsYzBL._SX330_BO1,204,203,200_.jpg

https://images-na.ssl-images-amazon.com/images/I/81xZtBhLjEL.jpg

https://images-na.ssl-images-amazon.com/images/I/51v-zo8SXkL._SX331_BO1,204,203,200_.jpg

https://images-na.ssl-images-amazon.com/images/I/91nHC-xa5KL.jpg

https://upload.wikimedia.org/wikipedia/en/thumb/2/25/Never_Let_Me_Go.jpg/220px-Never_Let_Me_Go.jpg

https://images-na.ssl-images-amazon.com/images/I/A1rIzRwWNML._RI_.jpg

Stories:
https://kbimages1-a.akamaihd.net/6bd76f52-d8e7-48cf-9d4b-4460577f2ca5/353/569/90/False/regret-16.jpg

https://cdn3.volusion.com/zjhys.xrwrf/v/vspfiles/photos/FES1573221610-2.jpg

https://i0.wp.com/smithsonianapa.org/bookdragon/wp-content/uploads/sites/10/2010/08/Runaway.jpg?resize=300%2C453

https://images.penguinrandomhouse.com/cover/9780307272027

https://images.gr-assets.com/books/1320420418l/145007.jpg

https://images.gr-assets.com/books/1348707608l/266245.jpg

I used the following images in the workshops section:
http://authornews.penguinrandomhouse.com/wp-content/uploads/2016/02/fiction1.jpg

https://i.pinimg.com/originals/ae/fe/c4/aefec4b35fb758892dffcd5dd6157877.jpg

https://wab.org/wp-content/uploads/2018/01/Comedy1.jpg

https://dabbledoneright-production.s3.amazonaws.com/production/uploads/course/photo/93381/carousel_pearson-creative-writing.jpg

All images used are in _assets.
