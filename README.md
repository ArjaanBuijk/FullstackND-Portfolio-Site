# Portfolio

The portfolio page can be found in: **static/portfolio.html**

It is created with [pinegrow](https://pinegrow.com/), using [Bootstrap 4](https://getbootstrap.com/)

The base template is an empty Bootstrap 4: index.html



##### Navbar for branding

A bootstrap 4 [navbar](https://getbootstrap.com/docs/4.0/components/navbar/) is used for branding purposes only.

- The [Udacity logo](http://logo.kenh.net/logo/udacity.svg.html) is in SVG format.
- See [here](https://stackoverflow.com/questions/21155060/how-to-put-text-underneath-a-navbar-brand-in-bootstrap?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa) for explanation how to put a tag-line under the name.




##### Main image

I used the bootstrap class "img-fluid", which scales the image very nicely for different sizes.

The image had to be scaled to 1140px to completely fill the container for all screen sizes, including the **Extra Large** devices. See [Bootstrap 4.0: grid-options](https://getbootstrap.com/docs/4.0/layout/grid/#grid-options)



##### Featured work

I used Bootstrap cards to get a nice side-by-side layout of the projects.

I used links to animated gifs that are stored with the github projects.

One design decision was not to rescale the animated gifs to equal height. This is a subjective decision. To rescale the animated gifs would involve some image manipulation, so they have the same aspect ratio. 



##### Responsive

Bootstrap delivers automatically responsive behavior. I tested that it gives a nice layout on all displays, from xs (320 px) to XL (1280 px). 

I tested this in pinegrow, where it is possible to show the website in these different displays.