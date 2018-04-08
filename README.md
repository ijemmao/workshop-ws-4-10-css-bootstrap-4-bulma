# workshop-ws-4-10-css-bootstrap-4-bulma
workshop-ws-4-10-css-bootstrap-4-bulma created by GitHub Classroom

## Bootstrapping your first website!

In this tutorial, we demonstrate the ability of bootstrap to simplify the website design process. We focus on outlining a generic webpage to emphasize the use of pre-made bootstrap components and showcase Bootstrap's intuitive naming schemes and built-in grid system.

Here's what we'll have created by the end of this tutorial:

<img src=#>

### Starting from scratch

The first step of creating your new webpage is easy and begins here: https://getbootstrap.com/docs/4.0/getting-started/introduction/

<img src=#>

Copy and paste the `Starter template` code to `index.html`, and you're done! You've now connected your webpage to Bootstrap. You should see "Hello, world!" if you run index.html.

Rename your page by editing the text within <title></title> and delete <h1>Hello, world!</h1> so we can add more components later.

<img src=#>

### Using the Bootstrap Grid


### Adding Components

##### Navbar

Navigate to: https://getbootstrap.com/docs/4.0/components/navbar/.

Here, you'll see a lot of navbar options. We'll be using the very first option. Copy and paste the code and place it directly under the opening <body> tag. Reloading your page and resizing the browser will show you exactly how your navbar will scale.

##### Jumbotron

Navigate to: https://getbootstrap.com/docs/4.0/components/jumbotron/

Here, we're also using the first option. Copy and paste this code directly below the navbar you just created.

##### Card

Now we're going to put three cards in a row.

In order to align these cards properly, we'll be using the Bootstrap grid system.

Navigate to: https://getbootstrap.com/docs/4.0/layout/grid/.

Copy the first grid option, and paste this under the jumbotron code. Once this is done, you'll be able to see the grid you've just created. You're now ready to introduce the cards into your code.

Navigate to: https://getbootstrap.com/docs/4.0/components/card/

We'll be using the card style located under `Titles, text, and links`. Replace the text `One of the three columns` with the associated card code. Note that these comes with a preset width, so remove `style="width: 18rem"` from `<div class="card">`.

##### Collapse - Accordion

You can also split up a grid system into larger and smaller partition. Here, we'll add a single card to the left side of the screen, and a larger accordion to its right.

Add a new row into the container you created when you copied over the original grid.

Lets create two columns: `<div class="col-sm-4"></div>` and `<div class="col-sm-8"></div>`.

Within `<div class="col-sm-4"></div>`, add a card by copy and pasting the associated code within the `<div>`.

Navigate to: https://getbootstrap.com/docs/4.0/components/collapse/

Within this webpage, there is an `Accordion` option. Copy and paste the code within `<div class="col-sm-8"></div>`. This accordion should be twice the width of the card.

Notice how there is no padding on the top or bottom of your rows. Add the class `mb-4` to the `div class="row"` to create the spacing.

Note how the `<div>` with `id="collapseOne"` opens automatically upon refresh. If you would like to prevent it from doing so, delete the `show` class from this `<div>`.

##### Footer

Creating a footer using Bootstrap takes a bit more manual work. Within the same container and below our second row, begin by creating a `<footer>`. Assign it the class `row`, such that your code looks like this: `<footer class="row">`.

For aesthetic purpose, we want to add a border to this. Add the class `border-top` to `<footer>`.

In this row, lets add four columns, each with class `col-sm and mt-4`.`mt-4` will add a margin at the top of each column.

In the first columns, we include the code:
  `<img class="mb-2" src="https://getbootstrap.com/assets/brand/bootstrap-solid.svg" alt="" width="24" height="24">
  <small class="d-block mb-3 text-muted">© 2017-2018</small>`
This adds the Bootstrap logo to that div.

For the other three columns, lets add some links like we did in our first lab. Copy and paste this code into each:

  <h5>Link Header</h3>
  <ul class="list-unstyled">
    <li>First</li>
    <li>Second</li>
    <li>Third</li>
  </ul>

### Conclusions
### Additional Challenges
##### Carousel
Navigate to: https://getbootstrap.com/docs/4.0/components/carousel/

Let's add a carousel.
