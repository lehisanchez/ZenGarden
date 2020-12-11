Here is the completion of my efforts. Tweak it as you see fit!

The site is fully functional so the only thing left to do is to add SASS wherever we can.


There are plenty of areas in the code to add:
Nesting
Variables
Mixins





Walkthrough:

I've extracted all related CSS to their own file. (Typography, Animations, etc)

The big/important files where all the good stuff is are layout, typography, and animations

Not much is going on in the colors file.

The main.scss includes sass partials in the following order:

@use 'reset';
@use 'typography';
@use 'colors';
@use 'layout';
@use 'rocket';
@use 'animations';


FYI !!!!!!!!!   MEDIA QUERIES !!!!!!!


To keep things organized, each file has it's own Media Queries at the bottom. This can be changed. I just found it helpful to have the screen adjustments close by as I worked.

The breaking widths are 800px and 1100px.

Media Queries can be extracted out to their own files if you'd like.



FYI !!!!!!!!!   SASS CODE LIKE VARIABLES AND MIXINS !!!!!!!

@USE is a little different than @import

variables and mixins will need to stay in the files that they are used in.

There's a way to keep variables and mixins in their own files but including the variables
and mixins elsewhere in the code gets a little tricky

To save time, I would keep sass variables in the files that need them.



A possible weak point is the Archives section. I didn't know what to do there.


Feel free to text me if you have a question about anything!!!
