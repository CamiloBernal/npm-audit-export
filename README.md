# Npm Audit Export 🕵️‍♂️

![npm version](https://img.shields.io/npm/v/audit-export?style=flat-square)
![npm downloads](https://img.shields.io/npm/dt/audit-export?style=flat-square)

A convenient tool to **export npm audit results** to a comprehensive **offline HTML page**, providing a clear overview of your project's vulnerabilities.

> Inspired by [npm-audit-html](https://www.npmjs.com/package/npm-audit-html), but with more Node.js versions supported, offline support and lightweight ⚡

## Compatibility

**This package is compatible with Node.js versions 10 through 20, as well as future versions.**

## Installation

Install globally using npm:

```bash
npm install -g audit-export
```

## Usage

You can use `audit-export` with `npx audit-report` or install it globally for convenient access. Here are some usage options:

1. Export audit results to the default location (`./audit-report.html`):

    ```bash
    npm audit --json | audit-export
    ```

2. Export audit results to a specified folder:

    ```bash
    npm audit --json | audit-export ../any/folder/path
    ```

3. Export audit results to a specific file within a folder:

    ```bash
    npm audit --json | audit-export ../any/folder/path file-name.html
    ```

## Contributing

We welcome contributions from the community! Feel free to open issues and submit pull requests on our [GitHub Issues page](https://github.com/hotaydev/audit-export/issues). Your feedback and suggestions are highly appreciated.

## Download

You can download the package from [npm](https://www.npmjs.com/package/audit-export).

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/hotaydev/audit-export/blob/main/LICENSE) file for details.

Happy auditing! 🛡️🚀