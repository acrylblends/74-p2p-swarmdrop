# Swarmdrop

A peer-to-peer transfer-room prototype showing peer discovery, chunk availability, transfer progress and integrity verification using synthetic local state.

An ACRYL Blends blueprint for the **Peer-to-Peer** category (`acrylblends.p2p-swarmdrop`, category 74 of 100).

Status: designed, being built. `design/spec.md` is the specification and `design/mockup.html` the mockup (open it in a browser). The app itself,
composed from Cordis plugins (one `plugins/<feature>/` folder and one `blend.yaml` row per feature), lands here when it passes review.

When it is ready you will start it with:

```sh
npm create acrylblends@latest my-app -- --from acrylblends.p2p-swarmdrop
cd my-app && npm install && npm run dev
```

Listed on https://acrylblends.github.io/blends and https://acryl.dev/blends.
