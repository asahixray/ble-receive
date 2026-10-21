# ble-receive

testViewer の「Share to Phone (BLE)」で送った画像を Android Chrome (Web Bluetooth) で受け取るページ。
元は testViewer リポジトリの `experiments/ble-share/web/receive.html`。

- 画像は BLE で PC から直接届き、このページの配信元 (GitHub Pages) には送られない
- 復号の鍵は QR の URL の `#` 以降にだけあり、サーバには送られない
