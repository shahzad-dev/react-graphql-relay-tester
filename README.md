# React, GraphQL & Relay Playground

This project includes an app server, a GraphQL server, relay and a transpiler that you can use to test Graphql, Relay and React components.

## Installation

```
npm install
```

## Running

Start a local server:

```
npm start
```

## Developing

Any changes you make to files in the `js/` directory will cause the server to
automatically rebuild the app and refresh your browser.

If at any time you make changes to `data/schema.js`, stop the server,
regenerate `data/schema.json`, and restart the server:

```
npm run update-schema
npm start
```

## References:

- For a walkthrough, see the [Relay tutorial](https://facebook.github.io/relay/docs/tutorial.html).
- [ES6 Quick Guide](http://es6-features.org).
- [Graphql](http://graphql.org/learn/).
- [Relay](https://facebook.github.io/relay/docs/tutorial.html)
- [React Tutorial](https://scotch.io/tutorials/learning-react-getting-started-and-concepts)
- [Babel Try it out](https://babeljs.io/repl/).
