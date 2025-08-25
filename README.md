# 🎉 prettier-hook - Modify Prettier for Your Needs

[![Download](https://img.shields.io/badge/Download-v1.0.0-brightgreen)](https://github.com/xxpedrodavidxx/prettier-hook/releases)

## 🚀 Getting Started

Welcome to **prettier-hook**! This tool helps you adjust your JavaScript code formatting using Prettier. Even if you’re not a programmer, you can easily set this up on your computer. Follow the steps below to get started.

## 📥 Download & Install

1. Visit the Releases page to download the latest version of prettier-hook: [Download Here](https://github.com/xxpedrodavidxx/prettier-hook/releases).

2. Once you reach the page, find the latest version labeled with the highest number.

3. Click on the version link to see the available files. Choose the appropriate file for your system and click to download.

4. After the file has downloaded, follow the installation instructions specific to your operating system:

   - **Windows**: Run the `.exe` file by double-clicking. It will guide you through the setup.
   - **MacOS**: Open the `.dmg` file and drag the app to your Applications folder.
   - **Linux**: Use the terminal to extract the downloaded package and follow instructions provided in the README.

5. Once the installation completes, you can start using prettier-hook.

## 🖥️ Requirements

To use prettier-hook, ensure you have the following installed on your system:

- Node.js version 12 or higher. You can download it from [Node.js Official Website](https://nodejs.org/).
- A code editor, like Visual Studio Code, that supports JavaScript and TypeScript.

## 📋 How to Use

After installing, follow these steps to use prettier-hook:

1. Open your terminal or command prompt.

2. Use the following command, replacing `<filepath>` with the path to the file you want to modify:

   ```sh
   npx prettier-hook --require <filepath>
   ```

   Or, if you prefer Yarn:

   ```sh
   yarn prettier-hook --require <filepath>
   ```

3. For example, you can modify a file called `example.js` like this:

   ```sh
   npx prettier-hook --require path/to/example.js
   ```

4. With prettier-hook, you can customize how your files look. You can change JavaScript `require` statements to `import` statements, for better compatibility with modern code.

## 🌟 Example Code

Here’s a simple example to see prettier-hook in action. You can convert `require` to `import` statements as follows:

### Original File: `examples/simple/test.js`

```js
const fs = require('fs');
```

### Command to Run

```sh
$ DEBUG=1 yarn ts-node dist/bin/prettier-hook.js --require examples/simple/index.ts examples/simple/test.js
```

### Converted File: `examples/simple/test.js`

```js
import * as fs from 'fs';
```

This command will modify your file and apply the changes through prettier-hook.

## 📚 Use Cases

prettier-hook is useful in many situations. Here are some examples:

- Convert JavaScript files to TypeScript files with ease.
- Update legacy codebases to modern standards using `import` syntax.

These use cases ensure that your JavaScript code remains clean and maintainable.

## 🔗 Additional Resources 

For more information or detailed instructions, you may refer to the following resources:

- [prettier-hook Documentation](https://github.com/xxpedrodavidxx/prettier-hook)
- [JavaScript to TypeScript Converter](https://github.com/suguru03/javascript2typescript)
- [TypeG Documentation](https://github.com/suguru03/typeg)

## ❓ Troubleshooting

In case you face any issues, check the following:

- Ensure that Node.js is properly installed and added to your system path.
- Verify that you are using the correct commands in your terminal.
- If you run into permission issues, try running your terminal as an administrator.

By following these steps, you can successfully install and run prettier-hook, making your code formatting process simpler and more efficient.

## 📬 Feedback

We would love to hear your thoughts or any suggestions you have. Feel free to reach out by opening an issue in the repository. 

By using prettier-hook, you will streamline your code formatting and ensure your projects remain clean and organized.