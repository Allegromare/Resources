
Ustariz Enzo
Posted on 26 ott 2021 • Edited on 18 feb 2022

Bottom navigation for mobile screens
#html #css #mobile #tutorial

Hey fellow creators,

Let's learn how to create a dead easy bottom navigation for small screens!

Navigation bar on the bottom of the screen


If you prefer to watch the video version, it's right here :
https://youtu.be/nG_BFzE8Cgk


1. The HTML Structure.
Create a navigation with your links. Here, I am using svg files that I organised in a folder called "ressources".



<body>
    <nav class="mobile-nav">
        <a href="#" class="bloc-icon">
            <img src="ressources/home.svg" alt="">
        </a>
        <a href="#" class="bloc-icon">
            <img src="ressources/heart.svg" alt="">
        </a>
        <a href="#" class="bloc-icon">
            <img src="ressources/magnifying-glass.svg" alt="">
        </a>
        <a href="#" class="bloc-icon">
            <img src="ressources/plus.svg" alt="">
        </a>
        <a href="#" class="bloc-icon">
            <img src="ressources/user.svg" alt="">
        </a>
    </nav>
</body>


2. Style the navigation bar.
First, let's style the navigation bar at the bottom of the screen and make sure to space each icon evenly.



.mobile-nav {
  background: #F1F1F1;
  position: fixed;
  bottom: 0;
  height: 65px;
  width: 100%;
  display: flex;
  justify-content: space-around;
}


Then, center the icons horizontally and vertically in the navigation bar.



.bloc-icon {
  display: flex;
  justify-content: center;
  align-items: center;
}


You also need to adjust the size of your icons so that they're neither too small nor too big. I'll size them down like so:



.bloc-icon img {
  width: 30px;
}


3. Add a media query.
Since this is a navigation bar only for mobile (or small screens), you need to add the following code so that the navigation will disappear for screens larger than 600 pixels.



@media screen and (min-width: 600px) {
  .mobile-nav {
  display: none;
  }
}


That's it! It's dead simple ;)

However, if you have more links in your nav, a bottom navigation like this wouldn't really work. Another option would then be the hamburger menu, but it's harder to use for average users, since they prefer a simpler nav like this.

You could also mix the two! For instance, your first or last link could be a hamburger menu, and once you click on it it could slide the menu on the left or right side of the screen.

Have fun coding!

Check out my Youtube channel: https://www.youtube.com/c/TheWebSchool

Enzo.
