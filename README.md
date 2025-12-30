#### hearthking.github.io



Disable Jekyll Processing (Important!)

GitHub Pages uses a tool called Jekyll by default. Sometimes, Jekyll ignores files starting with underscores or handles text files strictly. To ensure your app-ads.txt is served exactly as-is:

Create a blank file in your root directory named .nojekyll.

This tells GitHub to serve your files "raw," preventing any formatting issues that might break the AdMob crawler.



## Critical Configuration in Play Store/App Store

For this to work, the **Developer Website** URL in your Google Play Console or Apple App Store Connect must match your GitHub Pages URL.

| **Store Field**       | **Value to Enter**             |
| --------------------- | ------------------------------ |
| **Developer Website** | `https://hearthking.github.io` |
