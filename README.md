## Interceptor

### How to use
1. put your files under filed folder
2. open the `rules.json`
3. change the `condition.urlFilter`, match the url you want to intercept
4. change the `condition.resourceTypes`, script: a javascript file, stylesheet: a css file, and so on, reference: [chrome.declarativeNetRequest - Chrome for Developers](https://developer.chrome.com/docs/extensions/reference/declarativeNetRequest/#type-ResourceType)
5. change the `action.redirect.extensionPath`, relative to the files folder
6. open the `manifest.json`
7. change the `web_accessible_resources.resources`, input the files path you put under the files folder
8. open [chrome://extensions/](chrome://extensions/)
9. drag the project folder to install the plugin
10. refresh the page you want to intercept
