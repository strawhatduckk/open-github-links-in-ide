# Step-by-step instructions to install extension locally

Note: Setup instructions provided supports chromium based browsers.

1. Setup the repo
```
yarn && yarn build
```

2. Go to `chrome://extensions/.`
3. Enable `Developer mode` on the top right
4. Click on `Load unpacked`
![alt text](<docs/CleanShot 2024-09-13 at 11 .45.25@2x.png>)
5. Select the `./dist/chrome/manifest.json` file
6. Open the extension setting. Update the local path to where mozart lives, and choose `Cursor` as IDE.
![alt text](<docs/CleanShot 2024-09-13 at 11 .47.24@2x.png>)