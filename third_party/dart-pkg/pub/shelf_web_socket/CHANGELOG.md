## 0.2.1

* Fix all strong-mode warnings.

## 0.2.0

* **Breaking change**: `webSocketHandler()` now uses the
  [`WebSocketChannel`][WebSocketChannel] class defined in the
  `web_socket_channel` package, rather than the deprecated class defined in
  `http_parser`.

[WebSocketChannel]: https://www.dartdocs.org/documentation/web_socket_channel/latest/web_socket_channel/WebSocketChannel-class.html

## 0.1.0

* **Breaking change**: `webSocketHandler()` now passes a
  [`WebSocketChannel`][WebSocketChannel] to the `onConnection()` callback,
  rather than a deprecated `CompatibleWebSocket`.

[WebSocketChannel]: https://www.dartdocs.org/documentation/http_parser/2.1.0/http_parser/WebSocketChannel-class.html

## 0.0.1+5

* Support `http_parser` 2.0.0.

## 0.0.1+4

* Fix a link to `shelf` in the README.

## 0.0.1+3

* Support `http_parser` 1.0.0.

## 0.0.1+2

* Mark as compatible with version `0.6.0` of `shelf`.

## 0.0.1+1

* Properly parse the `Connection` header. This fixes an issue where Firefox was
  unable to connect.
