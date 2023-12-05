## TAURI-NOTES
### Installation
Create NextJs Application
```vim
$npx create-next-app@latest --use-npm
```
After Intallation Go to the App Folder
```vim
$cd todo-nextjs-app
```
Update next.config.js
```vim
/** @type {import('next').NextConfig} */
const nextConfig = {
  output: 'export', //Add This
}
module.exports = nextConfig
```
Then Install Tauri
```vim
$npm install --save-dev @tauri-apps/cli
```
Update your package.json
```vim
"scripts": {
  "tauri": "tauri" //Add This
}
```
Run tauri
```vim
$npm run tauri dev
```
### Reference

[Tauri Rust from Frontend](https://tauri.app/v1/guides/features/command)
