# Local Storage


## INTRODUCING HTML5 STORAGE:
 * HTML5 Storage: is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.” The naming situation is made even more complicated by some related, similarly-named, emerging standards that I’ll discuss later in this chapter.

 * ÷t’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.

 * The storage event is supported everywhere the localStorage object is supported, which includes Internet Explorer 8. IE 8 does not support the W3C standard addEventListener (although that will finally be added in IE 9). Therefore, to hook the storage event, you’ll need to check which event mechanism the browser supports. (If you’ve done this before with other events, you can skip to the end of this section. Trapping the storage event works the same as every other event you’ve ever trapped. If you prefer to use jQuery or some other JavaScript library to register your event handlers, you can do that with the storage event, too.)

 ![html5](https://lh3.googleusercontent.com/proxy/9lSFXqk9SVF83fsNugYt5mGTWzsqhiimmUmeBFWXvGT3Xq9cI-jmTpRPUIHftUtYOLo_DtG83-c222FYqzSy_5qEtvNnTuk_1icE6_09pCaqnSxh1aiHbg)

 ![cookise vs local storage](http://ic.pics.livejournal.com/dotnetinter/32561056/128955/128955_original.png)

![cookise vs local storage](https://image.slidesharecdn.com/usingcookiesandsessions-170309143201/95/using-cookies-and-sessions-2-638.jpg?cb=1489070001)
