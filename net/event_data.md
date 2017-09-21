<!-- YAML
added: v0.1.90
-->

* {Buffer}

Emitted when data is received.  The argument `data` will be a `Buffer` or
`String`.  Encoding of data is set by `socket.setEncoding()`.
(See the [Readable Stream][] section for more information.)
当发送的数据被接收时，'data'参数将会是'Buffer'类型或'String'类型。数据的类型可以通过`socket.setEncoding()`设置。

Note that the **data will be lost** if there is no listener when a `Socket`
emits a `'data'` event.

