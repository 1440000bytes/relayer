Combination of expensive and whitelisted relay
=============================================

Requires users to manually register themselves to be able to publish events and pay a fee except whitelisted pubkeys.

Running
-------

This requires a recent CLN version with Commando.

Environment variables:

    POSTGRESQL_DATABASE=postgresql://...
    CLN_NODE_ID=02fed8723...
    CLN_HOST=127.0.0.1:9735
    CLN_RUNE=...
    TICKET_PRICE_SATS=500
    WHITELIST=6681268ace4...

Compiling
---------


    go install github.com/1440000bytes/relayer/expensive@latest
