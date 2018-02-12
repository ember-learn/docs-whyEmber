
## Power of Productivity
When you install Ember (npm install ember-cli), you get the power of productivity.

Just by running ember new my-app, here’s what you get by default:

- Router
- Resolver (automatically discovers modules based on a set naming convention)
- Ember Data – loads data from your API & transforms the data into model objects (assumes JSON API and RESTful URLs)
- JS transpilation (ES2015+ to ES5)
- Pre-compiled templates
- Concatenation & minification
- A development server with live reload
- Test suite (QUnit)

If it’s not included- it’s typically only a command away (via addons) - this is a direct benefit of the “convention over configuration” approach.

1. Your team(s) will already have the benefit of increased productivity.
2. Other teams have had this benefit as well; many have used some of this time to give back in the form of an addon that provides additional functionality.
3. Because Ember embraces


## The Learning Curve

“But React is easier to Learn!”
So you start with React. But that’s only the view layer, so you have to add other things to your project.

- Gulp
- Redux
- Redux-storage
- BabelJS
- React-router
- React-router-redux
- Webpack
- Webpack Dev Server
- Jest
- Sass
- Autoprefixer

Now, all these things have different teams of maintainers, different code standards and different release cycles. Not only do you have to pick each one of these things (since they all have different options available), but you have to keep them all updated separately, too.
So is it really easier?


## Ember Engines

Ember engines is a way to encapsulate chunks of your own app in an Engine.
Engines can define their own routes, which that can be mounted into the host application’s router. Engines can be mounted several times, and have their own child engines, as well.
This supports smaller teams working on a bigger app- or even globally distributed teams working on a bigger app.
Engines can be set up to be lazily loaded as well, which means that you can define that a specific Engine shouldn’t be loaded until it’s needed. For example, maybe your app includes an admin dashboard, but only a small percentage of your users will ever use the admin dashboard. By making that engine lazyload,
