# Sender state fixtures

Static pages for exercising three sender initialization states:

- [Misconfigured](https://elohimmarron.github.io/sender-state-fixtures/misconfigured.html): starts the sender immediately.
- [Configured](https://elohimmarron.github.io/sender-state-fixtures/configured.html): starts the sender only when enabled.
- [Configured, sender disabled](https://elohimmarron.github.io/sender-state-fixtures/configured-disabled.html): initializes the sender in a disabled state, then enables it on request.

Serve the directory with any static file server, for example:

```sh
python3 -m http.server 8000
```
