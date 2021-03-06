# streamdata-android / stockmarket sample
This application shows how to use the <a href="http://streamdata.io" target="_blank">streamdata.io</a> proxy in a sample Android app.

Streamdata.io allows to get data pushed from various sources. This sample application shows simulated market data values pushed by Streamdata.io proxy using Server-sent events.

## License

* [Apache Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)


To run the sample, you can clone this GitHub repository, and then open the project with Android Studio.


## Add the Streamdata.io authentication token

Before running the project on a phone or emulator, you have to paste a token to be authenticated by the proxy.

Modify StockMarketList.java on line 44 :

```
private final String streamdataioAppToken = "YOUR_TOKEN_HERE";
```

To get a token, please sign up for free to the <a href="https://portal.streamdata.io/" target="_blank">streamdata.io portal</a> and follow the guidelines. You will find your token in the 'security' section.

## Project dependencies


The application dependencies are available on GitHub

* JSON library : <a href="https://github.com/FasterXML/jackson-databind" target="_blank">https://github.com/FasterXML/jackson-databind</a>
* JSON Patch : <a href="https://github.com/fge/json-patch" target="_blank">https://github.com/fge/json-patch</a>
* Server-Sent-Event : <a href="https://github.com/tylerjroach/eventsource-android/" target="_blank">https://github.com/tylerjroach/eventsource-android/</a>


If you have any questions or feedback, feel free to contact us at <a href="mailto://support@streamdata.io">support@streamdata.io</a>

Enjoy!
