# Sender state fixtures

Small static pages for exercising three sender initialization states:

- `misconfigured.html`: starts the sender immediately.
- `configured.html`: starts the sender only when enabled.
- `configured-disabled.html`: initializes the sender in a disabled state, then enables it on request.

Serve the directory with any static file server, for example:

```sh
python3 -m http.server 8000
```
