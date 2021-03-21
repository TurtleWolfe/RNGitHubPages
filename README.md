# [https://turtlewolfe.github.io/RNGitHubPages/](https://turtlewolfe.github.io/RNGitHubPages/ 'React Native GitHub Pages')

[expo GitHub Pages](https://docs.expo.io/distribution/publishing-websites/#github-pages 'gh-pages -d web-build')

[repo Source Code](https://github.com/TurtleWolfe/RNGitHubPages 'RNGitHubPages')

```bash
sudo npm install -g expo-cli
expo init RNGitHubPages --npm
cd RNGitHubPages
# expo i -D gh-pages
# expo i --save-dev gh-pages
# expo i gh-pages -D
npm i -D gh-pages
git remote add origin https://github.com/TurtleWolfe/RNGitHubPages.git
git push --set-upstream origin master
npm run deploy
```

[Picking an image](https://docs.expo.io/tutorial/image-picker/ 'For this, we can use an Expo library called expo-image-picker:')

```bash
expo install expo-image-picker
expo install expo-sharing
```

[Sharing the image](https://docs.expo.io/tutorial/sharing/ 'Similar to expo-image-picker, the functionality that we need to share is available in an Expo library — this one is called expo-sharing.')
