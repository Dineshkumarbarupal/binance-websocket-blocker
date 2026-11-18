Binance Market WebSocket Blocker (Manifest V3)

What it blocks:
- WebSocket handshakes matching stream.binance.com/stream

What it does not block:
- Other Binance WebSocket endpoints, such as ws-api.binance.com
- Ordinary HTTP/HTTPS requests

Install in Chrome or Microsoft Edge:
1. Extract this ZIP to a normal folder.
2. Open chrome://extensions or edge://extensions.
3. Turn on Developer mode.
4. Choose Load unpacked.
5. Select the extracted folder containing manifest.json and rules.json.
6. Reload the Binance tab once.

Important:
The extension blocks new WebSocket handshakes. It cannot directly terminate a connection that was already established before the extension was enabled. Reloading the Binance tab closes the old page connection; the blocked endpoint should then fail to reconnect.

To re-enable the live stream:
- Disable/remove this extension, then reload the Binance tab.
