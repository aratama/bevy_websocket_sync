# bevy_websocket_sync

Experimental real-time syncing code snippet for the Bevy Engine using WebSocket.

## Usage

Add `.env` as:

```
url=ws://localhost:8080
```

Then, start WebSocket server:

```
$ cd serve
$ node server
```

Finally, start client:

```
$ trunk serve
```

# Demo

https://aratama.github.io/bevy_websocket_sync/

# References

- https://github.com/bevyengine/bevy/blob/main/examples/async_tasks/external_source_external_thread.rs
