## React Starter Kit — "[isomorphic](http://nerds.airbnb.com/isomorphic-javascript-future-web-apps/)" web app boilerplate &nbsp; <a href="https://github.com/kriasoft/react-starter-kit/stargazers"><img src="https://img.shields.io/github/stars/kriasoft/react-starter-kit.svg?style=social&label=Star&maxAge=3600" height="20"></a> <a href="https://twitter.com/ReactStarter"><img src="https://img.shields.io/twitter/follow/ReactStarter.svg?style=social&label=Follow&maxAge=3600" height="20"></a>

[React Starter Kit](https://www.reactstarterkit.com) is an opinionated boilerplate for web
development built on top of [Node.js](https://nodejs.org/),
[Express](http://expressjs.com/), [GraphQL](http://graphql.org/) and
[React](https://facebook.github.io/react/), containing modern web development
tools such as [Webpack](http://webpack.github.io/), [Babel](http://babeljs.io/)
and [Browsersync](http://www.browsersync.io/). Helping you to stay productive
following the best practices. A solid starting point for both professionals
and newcomers to the industry.

**See** [getting started guide](./docs/getting-started.md), [demo][demo],
[docs](https://github.com/kriasoft/react-starter-kit/tree/master/docs),
[roadmap](https://github.com/kriasoft/react-starter-kit/projects/1) &nbsp;|&nbsp;
**Join** [#react-starter-kit][chat] chat room on Gitter &nbsp;|&nbsp;
**Visit our sponsors**:<br><br>

[![Rollbar - Full-stack error tracking for all apps in any language](https://koistya.github.io/files/rsk/rollbar.png)](https://rollbar.com/?utm_source=reactstartkit(github)&utm_medium=link&utm_campaign=reactstartkit(github)) &nbsp;&nbsp;
[![Localize - Translate your web app in minutes](https://koistya.github.io/files/rsk/localize.png)](https://localizejs.com/?cid=802&utm_source=rsk)


### Getting Started

  * Follow the [getting started guide](./docs/getting-started.md) to download and run the project
    ([node](https://nodejs.org/) >= 5,
    **[node-gyp](https://github.com/nodejs/node-gyp#readme)**
    and **[prerequisites](https://github.com/nodejs/node-gyp#installation)**)
  * Check the [code recipes](./docs/recipes) used in this boilerplate, or share yours


### Customization

The `master` branch of React Starter Kit doesn't include a Flux implementation or any other
advanced integrations. Nevertheless, we have some integrations available to you in *feature*
branches that you can use either as a reference or merge into your project:

  * [feature/redux](https://github.com/kriasoft/react-starter-kit/tree/feature/redux) — isomorphic
    Redux by [Pavel Lang](https://github.com/langpavel)
    (see [how to integrate Redux](./docs/recipes/how-to-integrate-redux.md)) (based on `master`)
  * [feature/react-intl](https://github.com/kriasoft/react-starter-kit/tree/feature/react-intl) —
    isomorphic Redux and React Intl by [Pavel Lang](https://github.com/langpavel)
    (see [how to integrate React Intl](./docs/recipes/how-to-integrate-react-intl.md)) (based on `feature/redux`)
  * [feature/bootstrap3](https://github.com/kriasoft/react-starter-kit/tree/feature/bootstrap3) —
    Simplest possible integration of [react-bootstrap](https://react-bootstrap.github.io/)
    by [Pavel Lang](https://github.com/langpavel) (based on `master`)

If you think that any of these features should be on `master`, or vice versa, some features should
removed from the `master` branch, please [let us know](https://gitter.im/kriasoft/react-starter-kit).
We love your feedback!


### Comparison

<table width="100%">
  <tr>
    <th>&nbsp;</th>
    <th>
      <p>React Starter Kit</p>
      <a href="https://github.com/kriasoft/react-starter-kit"><img src="https://img.shields.io/github/stars/kriasoft/react-starter-kit.svg?style=social&label=~react-starter-kit" height="20"></a>
      <a href="https://twitter.com/ReactStarter"><img src="https://img.shields.io/twitter/follow/ReactStarter.svg?style=social&label=@ReactStarter" height="20"></a>
    </th>
    <th>
      <p>React Static Boilerplate</p>
      <a href="https://github.com/kriasoft/react-static-boilerplate"><img src="https://img.shields.io/github/stars/kriasoft/react-static-boilerplate.svg?style=social&label=~react-static-boilerplate" height="20"></a>
      <a href="https://twitter.com/ReactStatic"><img src="https://img.shields.io/twitter/follow/ReactStatic.svg?style=social&label=@ReactStatic" height="20"></a>
    </th>
    <th>
      <p>ASP.NET Core Starter Kit</p>
      <a href="https://github.com/kriasoft/aspnet-starter-kit"><img src="https://img.shields.io/github/stars/kriasoft/aspnet-starter-kit.svg?style=social&label=~aspnet-starter-kit" height="20"></a>
      <a href="https://twitter.com/dotnetreact"><img src="https://img.shields.io/twitter/follow/dotnetreact.svg?style=social&label=@dotnetreact" height="20"></a>
    </th>
  <tr>
  <tr>
    <th align="right">App type</th>
    <td align="center"><a href="http://nerds.airbnb.com/isomorphic-javascript-future-web-apps/">Isomorphic</a> (universal)</td>
    <td align="center"><a href="https://en.wikipedia.org/wiki/Single-page_application">Single-page application</a></td>
    <td align="center"><a href="https://en.wikipedia.org/wiki/Single-page_application">Single-page application</a></td>
  </tr>
  <tr>
    <th colspan="4">Frontend</th>
  <tr>
  <tr>
    <th align="right">Language</th>
    <td align="center">JavaScript (ES2015+, JSX)</td>
    <td align="center">JavaScript (ES2015+, JSX)</td>
    <td align="center">JavaScript (ES2015+, JSX)</td>
  </tr>
  <tr>
    <th align="right">Libraries</th>
    <td align="center">
      <a href="https://github.com/facebook/react">React</a>,
      <a href="https://github.com/ReactJSTraining/history">History</a>,
      <a href="https://github.com/kriasoft/universal-router">Universal Router</a>
    </td>
    <td align="center">
      <a href="https://github.com/facebook/react">React</a>,
      <a href="https://github.com/ReactJSTraining/history">History</a>,
      <a href="https://github.com/reactjs/redux">Redux</a>
    </td>
    <td align="center">
      <a href="https://github.com/facebook/react">React</a>,
      <a href="https://github.com/ReactJSTraining/history">History</a>,
      <a href="https://github.com/reactjs/redux">Redux</a>
    </td>
  </tr>
  <tr>
    <th align="right">Routes</th>
    <td align="center">Imperative (functional)</td>
    <td align="center">Declarative</td>
    <td align="center">Declarative, cross-stack</td>
  </tr>
  <tr>
    <th colspan="4">Backend</th>
  <tr>
  <tr>
    <th align="right">Language</th>
    <td align="center">JavaScript (ES2015+, JSX)</td>
    <td align="center">n/a</td>
    <td align="center">C#, F#</td>
  </tr>
  <tr>
    <th align="right">Libraries</th>
    <td align="center">
      <a href="https://nodejs.org">Node.js</a>,
      <a href="http://expressjs.com/">Express</a>,
      <a href="http://docs.sequelizejs.com/en/latest/">Sequelize</a>,<br>
      <a href="https://github.com/graphql/graphql-js">GraphQL</a></td>
    <td align="center">n/a</td>
    <td align="center">
      <a href="https://docs.asp.net/en/latest/">ASP.NET Core</a>,
      <a href="https://ef.readthedocs.io/en/latest/">EF Core</a>,<br>
      <a href="https://docs.asp.net/en/latest/security/authentication/identity.html">ASP.NET Identity</a>
    </td>
  </tr>
  <tr>
    <th align="right"><a href="https://www.quora.com/What-are-the-tradeoffs-of-client-side-rendering-vs-server-side-rendering">SSR</a></th>
    <td align="center">Yes</td>
    <td align="center">n/a</td>
    <td align="center">n/a</td>
  </tr>
  <tr>
    <th align="right">Data API</th>
    <td align="center"><a href="http://graphql.org/">GraphQL</a></td>
    <td align="center">n/a</td>
    <td align="center"><a href="https://docs.asp.net/en/latest/tutorials/first-web-api.html">Web API</a></td>
  </tr>
</table>


### How to Contribute

Anyone and everyone is welcome to [contribute](CONTRIBUTING.md) to this project. The best way to
start is by checking our [open issues](https://github.com/kriasoft/react-starter-kit/issues),
[submit a new issues](https://github.com/kriasoft/react-starter-kit/issues/new?labels=bug) or
[feature request](https://github.com/kriasoft/react-starter-kit/issues/new?labels=enhancement),
participate in discussions, upvote or downvote the issues you like or dislike, send [pull
requests](CONTRIBUTING.md#pull-requests).


### Learn More

  * [Getting Started with React.js](http://facebook.github.io/react/)
  * [Getting Started with GraphQL and Relay](https://quip.com/oLxzA1gTsJsE)
  * [React.js Questions on StackOverflow](http://stackoverflow.com/questions/tagged/reactjs)
  * [React.js Discussion Board](https://discuss.reactjs.org/)
  * [Flux Architecture for Building User Interfaces](http://facebook.github.io/flux/)
  * [Enzyme — JavaScript Testing utilities for React](http://airbnb.io/enzyme/)
  * [Flow — A static type checker for JavaScript](http://flowtype.org/)
  * [The Future of React](https://github.com/reactjs/react-future)
  * [Learn ES6](https://babeljs.io/docs/learn-es6/), [ES6 Features](https://github.com/lukehoban/es6features#readme)


### Related Projects

  * [GraphQL Starter Kit](https://github.com/kriasoft/graphql-starter-kit) — Boilerplate for building data APIs with Node.js, JavaScript (via Babel) and GraphQL
  * [Membership Database](https://github.com/membership/membership.db) — SQL schema boilerplate for user accounts, profiles, roles, and auth claims
  * [Babel Starter Kit](https://github.com/kriasoft/babel-starter-kit) — Boilerplate for authoring JavaScript/React.js libraries


### Support

  * [#react-starter-kit](http://stackoverflow.com/questions/tagged/react-starter-kit) on Stack Overflow — Questions and answers
  * [#react-starter-kit](https://gitter.im/kriasoft/react-starter-kit) on Gitter — Watch announcements, share ideas and feedback
  * [GitHub issues](https://github.com/kriasoft/react-starter-kit/issues), or [Scrum board](https://waffle.io/kriasoft/react-starter-kit) — File issues, send feature requests
  * [appear.in/react](https://appear.in/react) — Open hours! Exchange ideas and experiences (React, GraphQL, startups and pet projects)
  * [@koistya](https://twitter.com/koistya) on [Codementor](https://www.codementor.io/koistya), or [Skype](http://hatscripts.com/addskype?koistya) — Private consulting


[rsk]: https://www.reactstarterkit.com
[demo]: http://demo.reactstarterkit.com
[node]: https://nodejs.org
[chat]: https://gitter.im/kriasoft/react-starter-kit
