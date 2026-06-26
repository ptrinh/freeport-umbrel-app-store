# Freeport Umbrel Community App Store

An [Umbrel](https://umbrel.com) community app store for self-hosting
[Freeport](https://freeport.trinh.uk) infrastructure.

## Install

1. In your Umbrel, open **App Store**.
2. Click the **⋯** menu (top right) → **Community App Stores**.
3. Add this store URL:

   ```
   https://github.com/ptrinh/freeport-umbrel-app-store
   ```

4. Open the **Freeport** store and install **Freeport Nostr MCP**.

## Apps

### Freeport Nostr MCP

A read-only Nostr [MCP](https://modelcontextprotocol.io) endpoint that doubles
as a Web Push / Expo push notifier for the Freeport network. Running it makes
your Umbrel an independent MCP host and notification host — no central server.

- MCP endpoint: `http://<umbrel>:8788/mcp`
- Source: https://github.com/ptrinh/freeport/tree/main/server

## License

MIT
