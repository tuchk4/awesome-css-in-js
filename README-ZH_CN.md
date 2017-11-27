# CSS in JS 相关类库
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/tuchk4/awesome-css-in-js.svg?branch=master)](https://travis-ci.org/tuchk4/awesome-css-in-js)


一个关于CSS in JS方法的很棒的集合

## 目录

- [Libraries](#libraries)
- [Articles](#articles)
- [Videos](#videos)
- [Benchmarks](#benchmarks)

## 库

- [fela](https://github.com/rofrischmann/fela/) - 通用的、动态的、高性能的JavaScript样式
- [styled-jss](https://github.com/cssinjs/styled-jss) - 在JSS上有样式的组件
- [react-jss](https://github.com/cssinjs/react-jss) - 在react中集成jss
- [jss](https://github.com/cssinjs/jss) - JSS是一种CSS创作工具，它使用JavaScript作为宿主语言
- [rockey](https://github.com/tuchk4/rockey) - 使用js的组件的Stressless CS. 编写基于组件的CSS和功能混合.
- [styled-components](https://github.com/styled-components/styled-components) - 通用的、动态的、高性能的JavaScript样式
- [aphrodite](https://github.com/Khan/aphrodite) - 它是内联样式，但他们工作!还支持通过CSS样式化
- [csx](https://github.com/jxnblk/cxs) - ϟ 一个cssin - js解决方案，用于功能性UI组件的功能性CSS
- [styled-jsx](https://github.com/zeit/styled-jsx) - 完整的CSS对JSX的支持
- [glam](https://github.com/threepointone/glam) - 在你的js中使用疯狂的css
- [glamor](https://github.com/threepointone/glamor) - 在你的js中使用css
- [glamorous](https://github.com/paypal/glamorous) - 通过优雅的API、小的足迹和出色的性能(通过glamor)来解决组件样式的问题
- [styletron](https://github.com/rtsao/styletron) - ⚡️ 通用、高性能JavaScript风格
- [radium](https://github.com/FormidableLabs/radium) - 在react元素上用于管理内联样式的工具集
- [aesthetic](https://github.com/milesj/aesthetic) - Aesthetic是用于样式组件的强大的react库，无论是使用对象的cssin - js，导入样式表，还是仅仅引用外部类名。
- [j2c](https://github.com/j2css/j2c) - CSS在JS库中，小巧而又有特点


> 注释表还没有完成。如果有bug或需要添加另一个库，请建议PR。

如何阅读表格:

**As Object** - 当使用对象声明CSS时。
```js
{
  color: 'red',
}
```

**As TL** - 当使用模板文本声明CSS时。
```js
`
  color: red;
`
```

**SSR** - 服务端渲染。

**RN Support** - React Native支持。

**Agnostic** - 框架不可知的。 意味着这个库可以用于任何框架。

**Dynamic** - 当可以编写依赖于运行时值的CSS时，就像组件道具一样。
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

**Babel plugins** - 如果有任何用于性能优化的babel插件。

**Bindings** - 如果有为另一个框架或库提供绑定的包。

| Package | As Object | As TL | SSR | RN Support | Agnostic | Dynamic | Babel plugins | Bindings |
|:-----------------:|:-------------:|:------------------------:|:--------------------:|----------------------|--------------------|-------------|---------------|----------|
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


## 文章

- [A Unified Styling Language](https://medium.com/seek-blog/a-unified-styling-language-d0c208de2660) - 为什么在JavaScript中写你的样式并不是一个可怕的想法，为什么我认为你应该关注这个快速发展的空间。
- [Is CSS-in-JS really bad for UX?](https://medium.com/@okonetchnikov/is-css-in-js-really-bad-for-ux-e9cce7b2da83) - CSS在JS性能方面的影响——JS开发人员过于专注于DX，而忘记了用户体验的重要性。
- [I swore never to use CSS in JS, here are 6 reasons why I was wrong](https://hackernoon.com/i-swore-never-to-use-css-in-js-here-are-6-reasons-why-i-was-wrong-541fe3dfdeb7)- “当我第一次听说这个想法的时候，我震惊了……”但这里有6个原因，为什么它有用。
- [Journey to Enjoyable, Maintainable Styling with React, ITCSS, and CSS-in-JS](https://medium.com/maintainable-react-apps/journey-to-enjoyable-maintainable-styling-with-react-itcss-and-css-in-js-632cfa9c70d6) - 用更好的CSS /带有组件/ JavaScript和最终的方法，使用ITCSS和Aphrodite
- [Rockey. Motivation and Requirements](https://medium.com/@tuchk4/rockey-motivation-and-requirements-f787d1ed61e0) - 关于JS方法中的CSS需求和在JS库中开发另一个CSS的动机——rockey。
- [CSS in JS: The Argument Refined](https://medium.com/@steida/css-in-js-the-argument-refined-471c7eb83955)
- [Inline Styles are so 2016](https://medium.com/yplan-eng/inline-styles-are-so-2016-f100b79dafe1)
- [“Scale” FUD and Style Components](https://medium.learnreact.com/scale-fud-and-style-components-c0ce87ec9772)
- [JSS is a better abstraction over CSS](https://top.fse.guru/jss-is-css-d7d41400b635)
- [A 5-minute Intro to Styled Components](https://medium.freecodecamp.com/a-5-minute-intro-to-styled-components-41f40eb7cd55)
- [Styled Components: Enforcing Best Practices In Component-Based Systems](https://www.smashingmagazine.com/2017/01/styled-components-enforcing-best-practices-component-based-systems/)
- [💅 styled components 💅 — Production Patterns](https://medium.com/@jamiedixon/styled-components-production-patterns-c22e24b1d896)
- [Introducing glamorous 💄](https://hackernoon.com/introducing-glamorous-fb3c9f4ed20e)

## 视频
- [Styling React/ReactNative Applications - Max Stoiber at React Amsterdam](https://www.youtube.com/watch?v=bIK2NwoK9xk)
- [CSS in JS tech chat with Kent C. Dodds and Sarah Drasner](https://www.youtube.com/watch?v=BXOF_8jDdf8)
- [CSS in JS without Compromise by François de Campredon at react-europe 2016](https://www.youtube.com/watch?v=DGEFNBYJRps)
- [Glamorous Walkthrough by Kent C. Dodds](https://www.youtube.com/watch?v=lmrQTpJ_3PM)
- [ColdFront16 • Glenn Maddern: The Future of Reusable CSS](https://www.youtube.com/watch?v=XR6eM_5pAb0)
- [Ryan's Random Thoughts on Inline Styles by Ryan Florence](https://www.youtube.com/watch?v=EkPcGS4TzdQ)


## 基准测试和比较
- [tuchk4/css-in-js-app](https://github.com/tuchk4/css-in-js-app) - 使用不同的cssin - js方法和库进行应用。
- [A-gambit/CSS-IN-JS-Benchmarks](https://github.com/A-gambit/CSS-IN-JS-Benchmarks) [RESULTS.md](https://github.com/A-gambit/CSS-IN-JS-Benchmarks/blob/master/RESULT.md)
- [hellofresh/css-in-js-perf-tests](https://github.com/hellofresh/css-in-js-perf-tests) - CSS-in-JS性能测试
- [jsperf: jss-vs-css](https://jsperf.com/jss-vs-css/3)
- [jsperf: classes vs inline styles](https://jsperf.com/classes-vs-inline-styles/4)
- [MicheleBertoli/css-in-js](https://github.com/MicheleBertoli/css-in-js) React: CSS in JS 技术比较。
