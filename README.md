# tickerct

Golang constant time ticker.
This ticker will not drop ticks as the standard time.Ticker will.
Usefull for applications that want to process something in an almost realtime manner

## Why

This ticker was created well testing different integrations in [mumble-discord-bridge](https://github.com/Stieneee/mumble-discord-bridge).
There are benchmarking tests in the mumble-discord-bridge repo.
This code was moved here as it will not be used in that repo moving forward.
