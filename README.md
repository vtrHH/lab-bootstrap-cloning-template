<p align="center"><img width="250" src="https://i.imgur.com/lMo1s1G.png"/></p>

# Cloning with Bootstrap

In this Lab we'll be reproducing an existing design using Bootstrap.

The [Significa](https://significa.co/) website is a beautiful example of what can be achieved with some simple styling and a minimalist mindset.

![Significa Base](https://raw.githubusercontent.com/josecarneiro/lab-bootstrap-cloning-template/master/template.png)

## Deliverables

You should aim to build a website that is as close to the original design as possible, while using as little custom CSS as possible.

## Instructions

First, let's download Bootstrap from the [official website](https://getbootstrap.com). Select the compiled CSS + JS version, and download the `.zip` file. Inside, you'll find some of the pre-compiled Bootstrap files that we'll need to develop our Bootstrap-based website.

Copy the `css/bootstrap.min.css` file to the folder `style`.

Inside of the `head` tag in our `index.html` let's import the following CSS files:

- The minified version of Bootstrap's stylesheets, `style/bootstrap.min.css`.
- Our custom styles, `styles/index.css`.

As an alternative to downloading the Bootstrap pre-compiled files, you might want to [link to their self-hosted files](https://getbootstrap.com/docs/4.4/getting-started/introduction/#css) instead.

### Iteration 1: Build the general layout

To start, focus on the [general layout](https://getbootstrap.com/docs/4.3/layout/overview/) of the page. Use semantically appropriate HTML tags to outline the contents of your page, and include Bootstrap [components](https://getbootstrap.com/docs/4.3/components/) when relevant.

Don't waste time on the minutia at this stage. Your priority should be placing things where they should be.

At this stage, you'll find its particularly useful to use the following Bootstrap classes: `container`, `row` and `col`.

Remember, you are not allowed to use custom CSS at this stage.

### Iteration 2: Apply utility classes

It's time to make things look good.

Using Bootstrap [utility classes](https://getbootstrap.com/docs/4.3/utilities/), try to approximate your page as much as possible to the original.

Remember, you are not allowed to use custom CSS at this stage.

### Iteration 3: Add custom CSS

Now lets make it perfect.

By writing custom CSS in the `style/index.css` file, you should make your website look as close as possible to the original. You might want to use a custom font loaded from the [Google Fonts website](https://fonts.google.com/).

### Bonus | Iteration 4: Deploy

Deploy your project to [Netlify](https://www.netlify.com).

**Happy Coding!** 💙
