# Lab8-Starter (Katy Stadler A17301232)

[Lab 8 Site](https://kstad21.github.io/Lab8_Starter/)

### Paragraph about how graceful degradation and service workers are related:

Graceful degradation is the principle of making sure that your app still works on older browsers/environments, even if the newer more advanced features aren't supported. Basically, your application shouldn't break on an older browser. Service workers are an example of this because they run independently from the DOM. As we learned, Javascript is single-threaded so they add on extra performance and offline enhancements, by virtue of providing background threads. Without them, the app will not break -- the core functionality will still be there. This is graceful degradation, since we build our app with enhancements but also a graceful way for our app to present if those enhancements aren't available on an older browser.
