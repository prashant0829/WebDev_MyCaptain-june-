# Introduction to Bulma

## Topics of the day.

## what is bulma ?

Bulma is a simple, elegant, and modern CSS framework that a lot of developers prefer over Bootstrap. Personally, I think Bulma has a better design by default, and it also feels more light-weight.

<!-- <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bulma/0.6.2/css/bulma.min.css"> -->

## 1. Setting up bulma.

Setting up Bulma is super easy, and you can do it in several different ways, whether you prefer NPM, downloading it directly from the docs, or using a CDN. We’re just going to link to a CDN from our HTML file, like this:

## 2. Modifiers

.
The first thing you should learn about Bulma is the modifier classes. These allow you to set alternative styles to almost all of the Bulma elements. They all start with is-_ or has-_, and then you replace the \* with the style you want.

<!-- example -->

## Buttons

To turn a normal button into a Bulma button, we’ll simply give it the class of button.

<!-- <button class="button">Click here</button>
 -->
<!-- result  -->

has a nice flat design by default. To change the styling, we’ll use Bulma modifiers. Let’s start off by making the button bigger, green, and with rounded corners

<!-- <button class="button **is-large is-success is-rounded**">Click here</button>
 -->

You can also use modifiers to control the state of buttons. Let’s, for example, add the class is-focused, which adds a border around it:

## 3.Columns

At the core of any CSS framework is how they solve columns, as that’s relevant for almost every website you’ll ever build. Bulma is based on Flexbox, so it’s really simple to create columns. Let’s create a row with four columns.

## example

<!-- <div class="columns">
  <div class="column">First column</div>
  <div class="column">Second column</div>
  <div class="column">Third column</div>
  <div class="column">Fourth column</div>
</div> -->

<!-- First, we’re creating a container <div> with a class of columns, and then we give each of the children a class of column. It results in the following: -->

## try this

## example

<!-- To give the columns colours, we can replace the text inside them with a <p> tag, and give it the notification class and an is-* modifier. -->

## use some more modeifiers

<!-- Let’s do this using the is-info, is-success, is-warning and is-danger  -->

## note : The notification class is actually meant for alerting users about something, as it allows you to fill the background with a colour using the is-\* modifiers

## modify width

## width modifiers

## Here are the options you can use for controlling the width of columns:

1. is-three-quarters
2. is-two-thirds
3. is-half
4. is-one-third
5. is-one-quarter
6. is-four-fifths
7. is-three-fifths
8. is-two-fifths
9. is-one-fifth

## hero section

1. . We’ll use the semantic <section>, and give it a class of hero and is-info to give it some colour. We also need to add a <div> child with the class hero-body.

<!-- example : <section class="hero is-success">
  -->

## you can also try this

  <!--
  <div class="container">
  <h1 class="title">Primary title</h1>
  <h2 class="subtitle">Primary subtitle</h2>
</div> 
   -->

## note: If we want it to be bigger, we can simply add is-medium on the <section> tag itself.

## example : <section class="hero is-info is-medium"> ...</section>

And that’s it!

## Awesome now you have got a basic taste of how bulma woirks

## homework

## 1.Make a registration form using bulma .
