# Troubleshooting

## Problem after installation (Windows OS):

I successfully installed Monaca Localkit, but after writing my credentials and pressing Sign In button, the UI freezes.

## Solution:

The problem might be in the installation of Node.js. If you installed Node.js through [.msi installer](https://nodejs.org/en/download/) on Node.js official website, we suggest you to use `NVM for Windows` to manage your Node.js versions instead.

1. Uninstall Node.js from your computer. Refer to this [manual](https://stackoverflow.com/questions/20711240/how-to-completely-remove-node-js-from-windows).
2. Install [NVM for Windows](https://github.com/coreybutler/nvm-windows#node-version-manager-nvm-for-windows).
3. After installation, download a Node.js version 14.19.0 and set this version to be used:
   ```bash
   $ nvm install 14.19.0
   $ nvm use 14.19.0
   ```
   For more information about managing multiple Node.js versions, refer to this [documentation](https://docs.microsoft.com/en-us/windows/dev-environment/javascript/nodejs-on-windows).
4. Install Monaca Localkit again.
5. The login should work now.
