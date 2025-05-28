# Lab8-Starter

Thanh-Long Nguyen-Trong

link: https://thanhlongnt.github.io/Lab8_Starter/

`How are graceful degradation and service workers related? (Answer this after doing the part below)`
Service workers are used to implement graceful degradation. They are able to intercept requests and cache them so that when network is unavailable the page content can still be loaded. Without service workers caching the page, it might not reload if we cut off the internet. 