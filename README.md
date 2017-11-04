# speech-polyfill
> **Under development**: This library is not released yet. You're free to try it out. I do NOT recommend to use it in production though. :bowtie:

This is a Polyfill for the HTML5 Speech Recognition API. It uses Microsoft's Cognitive Services as a backend. All Browsers supporting WebRTC will be supported by this Polyfill.

## Browser Support
For now I have tested the speech-polyfill on:

* Safari Desktop
* Mozilla Firefox Desktop
* Chrome Desktop
    * speech-polyfill will not apply, since Chrome has already support for it
* iOS (Safari, Chrome Firefox) **(Not working yet)**
* Opera **(Not working yet)**
* Edge

To be tested:
* Chrome on Android

## Prerequisites
* Azure Subscription [https://azure.microsoft.com](https://azure.microsoft.com)
* Create a new Cognitive Services container and select Bing Speech API to get an API key. Pass that key into the SpeechRecognition constructor.

## Get started
* get the polyfill with `yarn add speech-polyfill` or `npm install --save speech-polyfill`
* reference `node_modules/speech-polyfill/dist/speech-polyfill.js` in a Script Tag
    * you can also copy that file directly on your root folder
    * there is a min version in the `dist` folder. This file was not tested at all. It might not work.
* check out the sample App code [https://github.com/anteloe/speech-polyfill-sample](https://github.com/anteloe/speech-polyfill-sample)

I did not omit my API key. Use it if you want to quickly test the polyfill before creating an Azure Subscription. It is funded with my MSDN Subscription, be fair ;-)

## Demo
[https://speech-polyfill.azurewebsites.net/](https://speech-polyfill.azurewebsites.net/)
