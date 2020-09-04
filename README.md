# map-channels
A concurrency model

`connect {mapchannel} with {value}`: Adds `value` onto the `mapchannel` queue, returns an `IdentityToken` associated with that value.

`await {mapchannel} with {identity}`: Blocks until the result associated with the `identity` of the `mapchannel` can be retrieved, and returns it. 
