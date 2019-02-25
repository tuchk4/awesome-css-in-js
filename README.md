# Awesome CSS in JS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/tuchk4/awesome-css-in-js.svg?branch=master)](https://travis-ci.org/tuchk4/awesome-css-in-js)

A collection of awesome things regarding to CSS in JS approach

[中文 README](README-ZH_CN.md)
## Table of Contents

- [Libraries](#libraries)
- [Articles](#articles)
- [Videos](#videos)
- [Benchmarks](#benchmarks)

## Libraries

- [freestyler](https://github.com/streamich/freestyler) - 5<sup>th</sup> generation React styling library
- [emotion](https://emotion.sh/) - 👩‍🎤 The Next Generation of CSS-in-JS
- [fela](https://github.com/rofrischmann/fela/) - Universal, Dynamic & High-Performance Styling in JavaScript
- [styled-jss](https://github.com/cssinjs/styled-jss) - Styled Components on top of JSS
- [react-jss](https://github.com/cssinjs/react-jss) - JSS integration for React
- [jss](https://github.com/cssinjs/jss) - JSS is a CSS authoring tool which uses JavaScript as a host language
- [rockey](https://github.com/tuchk4/rockey) - Stressless CSS for components using JS. Write Component Based CSS with functional mixins.
- [styled-components](https://github.com/styled-components/styled-components) - Universal, Dynamic & High-Performance Styling in JavaScript
- [aphrodite](https://github.com/Khan/aphrodite) - It's inline styles, but they work! Also supports styling via CSS
- [csx](https://github.com/jxnblk/cxs) - ϟ A CSS-in-JS solution for functional CSS in functional UI components
- [styled-jsx](https://github.com/zeit/styled-jsx) - Full CSS support for JSX without compromises
- [glam](https://github.com/threepointone/glam) - crazy good css in your js
- [glamor](https://github.com/threepointone/glamor) - css in your javascript
- [glamorous](https://github.com/paypal/glamorous) - React component styling solved with an elegant API, small footprint, and great performance (via glamor)
- [styletron](https://github.com/rtsao/styletron) - ⚡️ Universal, high-performance JavaScript styles
- [radium](https://github.com/FormidableLabs/radium) - Set of tools to manage inline styles on React elements.
- [aesthetic](https://github.com/milesj/aesthetic) - Aesthetic is a powerful React library for styling components, whether it be CSS-in-JS using objects, importing stylesheets, or simply referencing external class names.
- [j2c](https://github.com/j2css/j2c) - CSS in JS library, tiny yet featureful


> NOTE table is still not completed. If there is bug or need to add another library - please suggest PR.

How to read the table:

**As Object** - When declare CSS using Objects.
```js
{
  color: 'red',
}
```

**As TL** - When declare CSS using Template Literals.
```js
`
  color: red;
`
```

**SSR** - Server Side Rendering.

**RN Support** - React Native support.

**Agnostic** - Framework agnostic. Means that library could used with any framework.

**Dynamic** - When it is possible to write CSS that depends on runtime values like component props.
```js
{
  color: props =>  props.color
}
```

```js
props => ({
  color: props.color
})
```

```js
`
  color: ${props => props.color}
`
```

**Babel plugins** - If there are any babel plugins for performance optimization.

**Bindings** - If there are packages that provide bindings for another framework or library.

| Package | As Object | As TL | SSR | RN Support | Agnostic | Dynamic | Babel plugins | Bindings |
|:-----------------:|:-------------:|:------------------------:|:--------------------:|----------------------|--------------------|-------------|---------------|----------|
| [emotion](https://github.com/emotion-js/emotion) | ✅ | ✅ | ✅ |  | ✅ | ✅ | ✅ | react-emotion, preact-emotion |
| [fela](https://github.com/rofrischmann/fela/) | ✅ |  | ✅ | ✅ | ✅ | ✅ |  | [react-fela](http://fela.js.org/docs/guides/UsageWithReact.html) [native-fela](http://fela.js.org/docs/guides/UsageWithReactNative.html) [preact-fela](http://fela.js.org/docs/guides/UsageWithPreact.html) [inferno-fela](http://fela.js.org/docs/guides/UsageWithInferno.html) |
| [jss](https://github.com/cssinjs/jss) | ✅ | ✅ | ✅ |  | ✅ | ✅ | ✅ | [react-jss](https://github.com/cssinjs/react-jss) [styled-jss](https://github.com/cssinjs/styled-jss) |
| [rockey](https://github.com/tuchk4/rockey) |  | ✅ |  |  | ✅ | ✅ |  | [rockey-react](https://github.com/tuchk4/rockey/tree/master/packages/rockey-react) |
| [styled-components](https://github.com/styled-components/styled-components) |  | ✅ | ✅ | ✅ |  | ✅ | ✅ |  |
| [aphrodite](https://github.com/Khan/aphrodite) | ✅ |  | ✅ |  | ✅ |  |  |  |
| [csx](https://github.com/jxnblk/cxs) | ✅ |  | ✅ |  | ✅ |  |  |  |
| [glam](https://github.com/threepointone/glam) |  | ✅ | ✅ |  | ✅ |  | ✅ |  |
| [glamor](https://github.com/threepointone/glamor) |  | ✅ | ✅ |  | ✅ |  | ✅ |  |
| [glamorous](https://github.com/paypal/glamorous) | ✅ |  | ✅ | ✅ |  | ✅ |  |  |
| [styletron](https://github.com/rtsao/styletron) | ✅ |  | ✅ |  | ✅ | ✅ |  | [styletron-react](https://github.com/rtsao/styletron#using-styletron-with-react) |
| [aesthetic](https://github.com/milesj/aesthetic) | ✅ |  |  |  | ✅ |  |  |  |
| [j2c](https://github.com/j2css/j2c) | ✅ |  | ✅ |  | ✅ |  |  |  | |


## Articles

- [A Unified Styling Language](https://medium.com/seek-blog/a-unified-styling-language-d0c208de2660) - why writing your styles in JavaScript isn’t such a terrible idea after all, and why I think you should be keeping an eye on this rapidly evolving space.
- [Is CSS-in-JS really bad for UX?](https://medium.com/@okonetchnikov/is-css-in-js-really-bad-for-ux-e9cce7b2da83) - CSS in JS performance implications - JS developers are too focused on DX and keep forgetting about how important performance for UX is.
- [I swore never to use CSS in JS, here are 6 reasons why I was wrong](https://hackernoon.com/i-swore-never-to-use-css-in-js-here-are-6-reasons-why-i-was-wrong-541fe3dfdeb7)- *"When I first heard of this idea, I was shocked..."* But here are 6 reasons why it is useful.
- [Journey to Enjoyable, Maintainable Styling with React, ITCSS, and CSS-in-JS](https://medium.com/maintainable-react-apps/journey-to-enjoyable-maintainable-styling-with-react-itcss-and-css-in-js-632cfa9c70d6) - Making Styling Better With better CSS / with Components / with JavaScript and final approach with ITCSS and Aphrodite
- [Rockey. Motivation and Requirements](https://medium.com/@tuchk4/rockey-motivation-and-requirements-f787d1ed61e0) - Article about requirements for CSS in JS approach and motivation to develop another one CSS in JS library - rockey.
- [CSS in JS: The Argument Refined](https://medium.com/@steida/css-in-js-the-argument-refined-471c7eb83955)
- [Inline Styles are so 2016](https://medium.com/yplan-eng/inline-styles-are-so-2016-f100b79dafe1)
- [“Scale” FUD and Style Components](https://medium.learnreact.com/scale-fud-and-style-components-c0ce87ec9772)
- [JSS is a better abstraction over CSS](https://top.fse.guru/jss-is-css-d7d41400b635)
- [A 5-minute Intro to Styled Components](https://medium.freecodecamp.com/a-5-minute-intro-to-styled-components-41f40eb7cd55)
- [Styled Components: Enforcing Best Practices In Component-Based Systems](https://www.smashingmagazine.com/2017/01/styled-components-enforcing-best-practices-component-based-systems/)
- [💅 styled components 💅 — Production Patterns](https://medium.com/@jamiedixon/styled-components-production-patterns-c22e24b1d896)
- [Introducing glamorous 💄](https://hackernoon.com/introducing-glamorous-fb3c9f4ed20e)

## Videos
- [Styling React/ReactNative Applications - Max Stoiber at React Amsterdam](https://www.youtube.com/watch?v=bIK2NwoK9xk)
- [CSS in JS tech chat with Kent C. Dodds and Sarah Drasner](https://www.youtube.com/watch?v=BXOF_8jDdf8)
- [CSS in JS without Compromise by François de Campredon at react-europe 2016](https://www.youtube.com/watch?v=DGEFNBYJRps)
- [Glamorous Walkthrough by Kent C. Dodds](https://www.youtube.com/watch?v=lmrQTpJ_3PM)
- [ColdFront16 • Glenn Maddern: The Future of Reusable CSS](https://www.youtube.com/watch?v=XR6eM_5pAb0)
- [Ryan's Random Thoughts on Inline Styles by Ryan Florence](https://www.youtube.com/watch?v=EkPcGS4TzdQ)
- [CSS in JavaScript](https://www.manning.com/livevideo/css-in-javascript-with-styled-components-and-react)


## Benchmarks and comparison
- [tuchk4/css-in-js-app](https://github.com/tuchk4/css-in-js-app) - React application with different css-in-js approaches and libraries.
- [A-gambit/CSS-IN-JS-Benchmarks](https://github.com/A-gambit/CSS-IN-JS-Benchmarks) [RESULTS.md](https://github.com/A-gambit/CSS-IN-JS-Benchmarks/blob/master/RESULT.md)
- [hellofresh/css-in-js-perf-tests](https://github.com/hellofresh/css-in-js-perf-tests) - CSS-in-JS performance tests
- [jsperf: jss-vs-css](https://jsperf.com/jss-vs-css/3)
- [jsperf: classes vs inline styles](https://jsperf.com/classes-vs-inline-styles/4)
- [MicheleBertoli/css-in-js](https://github.com/MicheleBertoli/css-in-js) React: CSS in JS techniques comparison.
