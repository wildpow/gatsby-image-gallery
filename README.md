# gatsby-image-gallery

<p align="center">
  <a href="https://github.com/browniebroke/gatsby-image-gallery/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="Released under the MIT license." />
  </a>
  <a href="https://travis-ci.com/browniebroke/gatsby-image-gallery">
    <img src="https://travis-ci.com/browniebroke/gatsby-image-gallery.svg?branch=master" alt="Build status." />
  </a>
  <a href="https://www.npmjs.com/package/@browniebroke/gatsby-image-gallery">
    <img src="https://img.shields.io/npm/v/@browniebroke/gatsby-image-gallery.svg" alt="Current npm package version." />
  </a>
  <a href="https://lgtm.com/projects/g/browniebroke/gatsby-image-gallery/alerts/">
    <img alt="Total alerts" src="https://img.shields.io/lgtm/alerts/g/browniebroke/gatsby-image-gallery.svg?logo=lgtm&logoWidth=18"/>
  </a>
</p>

Very basic gallery grid based on gatsby-image

## Install

```bash
npm install --save @browniebroke/gatsby-image-gallery
```

## Usage

```jsx
import React, { Component } from 'react'

import Gallery from '@browniebroke/gatsby-image-gallery'

class Example extends Component {
  render () {
    return (
      <Gallery />
    )
  }
}
```

## Development

### Releases

Releases should be automated using [semantic release](https://github.com/semantic-release/semantic-release).
This library parses the commit log to detect which version number should be bumped.

## License

MIT © [browniebroke](https://github.com/browniebroke)
