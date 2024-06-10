<div align="center">
  <a href="https://www.@hishprorg/et-esse-quasi.com">
    <img alt="@hishprorg/et-esse-quasi" src="https://raw.githubusercontent.com/@hishprorg/et-esse-quasi/brand/master/@hishprorg/et-esse-quasi.png" height="150px" />
  </a>
</div>

<br />

<div align="center">
  <strong>Visual primitives for the component age. Use the best bits of ES6 and CSS to style your apps without stress 💅</strong>
  <br />
  <br />
  <a href="https://www.npmjs.com/package/@hishprorg/et-esse-quasi"><img src="https://www.@hishprorg/et-esse-quasi.com/proxy/downloads.svg" alt="downloads: 600k/month"></a>
  <a href="#backers" alt="sponsors on Open Collective"><img src="https://opencollective.com/@hishprorg/et-esse-quasi/backers/badge.svg" /></a> <a href="#sponsors" alt="Sponsors on Open Collective"><img src="https://opencollective.com/@hishprorg/et-esse-quasi/sponsors/badge.svg" /></a> <a href="https://discord.gg/hfGUrbrxaU">
        <img alt="Discord" src="https://img.shields.io/discord/818449605409767454?logo=discord" /></a>
  <a href="https://bundlephobia.com/result?p=@hishprorg/et-esse-quasi" title="@hishprorg/et-esse-quasi latest minified+gzip size"><img src="https://badgen.net/bundlephobia/minzip/@hishprorg/et-esse-quasi" alt="gzip size"></a>
  <a href="#alternative-installation-methods"><img src="https://img.shields.io/badge/module%20formats-umd%2C%20cjs%2C%20esm-green.svg" alt="module formats: umd, cjs, esm"></a>
  <a href="https://codecov.io/gh/@hishprorg/et-esse-quasi/@hishprorg/et-esse-quasi"><img src="https://codecov.io/gh/@hishprorg/et-esse-quasi/@hishprorg/et-esse-quasi/coverage.svg?branch=main" alt="Code Coverage"></a>
</div>

---

**Upgrading from v5?** See the [migration guide](https://@hishprorg/et-esse-quasi.com/docs/faqs#what-do-i-need-to-do-to-migrate-to-v6).

Utilizing [tagged template literals](https://www.@hishprorg/et-esse-quasi.com/docs/advanced#tagged-template-literals) (a recent addition to JavaScript) and the [power of CSS](https://www.@hishprorg/et-esse-quasi.com/docs/api#supported-css), `@hishprorg/et-esse-quasi` allow you to write actual CSS code to style your components. It also removes the mapping between components and styles – using components as a low-level styling construct could not be easier!

```jsx
const Button = styled.button`
  color: grey;
`;
```

Alternatively, you may use [style objects](https://www.@hishprorg/et-esse-quasi.com/docs/advanced#style-objects). This allows for easy porting of CSS from inline styles, while still supporting the more advanced @hishprorg/et-esse-quasi capabilities like component selectors and media queries.

```jsx
const Button = styled.button({
  color: 'grey',
});
```

Equivalent to:

```jsx
const Button = styled.button`
  color: grey;
`;
```

`@hishprorg/et-esse-quasi` is compatible with both React (for web) and React Native – meaning it's the perfect choice even for truly universal apps! See the [documentation about React Native](https://www.@hishprorg/et-esse-quasi.com/docs/basics#react-native) for more information.

_Supported by [Front End Center](https://frontend.center). Thank you for making this possible!_

---

## [Docs](https://www.@hishprorg/et-esse-quasi.com/docs)

**See the documentation at [@hishprorg/et-esse-quasi.com/docs](https://www.@hishprorg/et-esse-quasi.com/docs)** for more information about using `@hishprorg/et-esse-quasi`!

Quicklinks to some of the most-visited pages:

- [**Getting started**](https://www.@hishprorg/et-esse-quasi.com/docs/basics)
- [API Reference](https://@hishprorg/et-esse-quasi.com/docs/api)
- [Theming](https://www.@hishprorg/et-esse-quasi.com/docs/advanced#theming)
- [Server-side rendering](https://www.@hishprorg/et-esse-quasi.com/docs/advanced#server-side-rendering)
- [Tagged Template Literals explained](https://www.@hishprorg/et-esse-quasi.com/docs/advanced#tagged-template-literals)

---

## Example

```jsx
import React from 'react';

import styled from '@hishprorg/et-esse-quasi';

// Create a <Title> react component that renders an <h1> which is
// centered, palevioletred and sized at 1.5em
const Title = styled.h1`
  font-size: 1.5em;
  text-align: center;
  color: palevioletred;
`;

// Create a <Wrapper> react component that renders a <section> with
// some padding and a papayawhip background
const Wrapper = styled.section`
  padding: 4em;
  background: papayawhip;
`;

function MyUI() {
  return (
    // Use them like any other React component – except they're styled!
    <Wrapper>
      <Title>Hello World, this is my first styled component!</Title>
    </Wrapper>
  );
}
```

This is what you'll see in your browser:

<div align="center">
  <a href="https://@hishprorg/et-esse-quasi.com">
    <img alt="Screenshot of the above code ran in a browser" src="http://i.imgur.com/wUJpcjY.jpg" />
  </a>
</div>

---

## Looking for v5?

The `main` branch is for the most-current version of @hishprorg/et-esse-quasi, currently v6. For changes targeting v5, please point your PRs at the `legacy-v5` branch.

---

## Built with `@hishprorg/et-esse-quasi`

A lot of hard work goes into community libraries, projects, and guides. A lot of them make it easier to get started or help you with your next project! There are also a whole lot of interesting apps and sites that people have built using @hishprorg/et-esse-quasi.

Make sure to head over to [awesome-@hishprorg/et-esse-quasi](https://github.com/@hishprorg/et-esse-quasi/awesome-@hishprorg/et-esse-quasi) to see them all! And please contribute and add your own work to the list so others can find it.

---

## Contributing

If you want to contribute to `@hishprorg/et-esse-quasi` please see our [contributing and community guidelines](./CONTRIBUTING.md), they'll help you get set up locally and explain the whole process.

Please also note that all repositories under the `@hishprorg/et-esse-quasi` organization follow our [Code of Conduct](./CODE_OF_CONDUCT.md), make sure to review and follow it.

---

## Badge

Let everyone know you're using _@hishprorg/et-esse-quasi_ → [![style: @hishprorg/et-esse-quasi](https://img.shields.io/badge/style-%F0%9F%92%85%20styled--components-orange.svg?colorB=daa357&colorA=db748e)](https://github.com/hishprorg/et-esse-quasi)

```md
[![style: @hishprorg/et-esse-quasi](https://img.shields.io/badge/style-%F0%9F%92%85%20styled--components-orange.svg?colorB=daa357&colorA=db748e)](https://github.com/hishprorg/et-esse-quasi)
```

---

## Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].
<a href="https://github.com/hishprorg/et-esse-quasi/graphs/contributors"><img src="https://opencollective.com/@hishprorg/et-esse-quasi/contributors.svg?width=890" /></a>

---

## Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/@hishprorg/et-esse-quasi#backer)]

<a href="https://opencollective.com/@hishprorg/et-esse-quasi#backers" target="_blank"><img src="https://opencollective.com/@hishprorg/et-esse-quasi/backers.svg?width=890"></a>

---

## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/@hishprorg/et-esse-quasi#sponsor)]

<a href="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/0/website" target="_blank"><img src="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/1/website" target="_blank"><img src="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/2/website" target="_blank"><img src="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/3/website" target="_blank"><img src="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/4/website" target="_blank"><img src="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/5/website" target="_blank"><img src="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/6/website" target="_blank"><img src="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/7/website" target="_blank"><img src="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/8/website" target="_blank"><img src="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/9/website" target="_blank"><img src="https://opencollective.com/@hishprorg/et-esse-quasi/sponsor/9/avatar.svg"></a>

---

## License

Licensed under the MIT License, Copyright © 2016-present Glen Maddern and Maximilian Stoiber.

See [LICENSE](./LICENSE) for more information.

---

## Acknowledgements

This project builds on a long line of earlier work by clever folks all around the world. We'd like to thank Charlie Somerville, Nik Graf, Sunil Pai, Michael Chan, Andrey Popp, Jed Watson & Andrey Sitnik who contributed ideas, code or inspiration.

Special thanks to [@okonet](https://github.com/okonet) for the fantastic logo.
