# Astro RESET CSS

## Table of Contents
- [Astro RESET CSS](#astro-reset-css)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)


## Introduction
This Astro component provides a CSS reset that is similar to the base styles in Tailwind CSS. It is designed to reset or normalize the default styles provided by the browser, and provide a consistent foundation for styling your Astro projects. The reset includes styles for commonly used HTML elements like headings, paragraphs, lists, and form elements, among others. By using this **Astro RESET CSS**, you can save time and ensure that your Astro projects have a consistent baseline of styles that are ready to be customized according to your project's needs.

## Installation
You can install **Astro RESET CSS** using npm:

```bash
npm install @appzic/astro-reset-css
```

## Usage

To use the `ResetCSS` Astro component in your project, simply add it to the head section of your `Layout.astro` file.

```astro
---
import ResetCSS from "@appzic/astro-reset-css"
---

<!DOCTYPE html>
<html lang="en">
    <head>
        ...
        <ResetCSS/>
        ...
    </head>
    <body>
        ...
    </body>
</html>

```

## Contributing
We welcome contributions from the community! Please take a look at our [CONTRIBUTING.md](./CONTRIBUTING.md) file for more information on how to get started. We appreciate all kinds of contributions, from bug reports and feature requests to code contributions and documentation improvements. Thank you for considering contributing to our project!

## License
**Astro RESET CSS** is licensed under the [MIT](./LICENSE) License.