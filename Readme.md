## Symfony Opentracing Messenger

This package helps you to setup opentracing on the [Symfony Messenger](https://symfony.com/doc/current/messenger.html) out of the box without any configs. 
This is just an addon for the [OpentracingBundleCore](https://github.com/auxmoney/OpentracingBundle-core).

If you are using Messenger for async messages no matter how many async messages you have inside message, it will trace them by modifying your messages before it gets processed. The way it modifies them is by using leveraging the [Symfony Messenger Events](https://symfony.com/doc/current/messenger.html#messenger-events)...

