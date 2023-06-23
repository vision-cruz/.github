# Streamer de video

Para iniciar con el streamer de video vamos a tener en cuenta que protocolos vamos a utilizar.

- Real Time Messaging Protocol `(RTMP)`  - Protocolo del stream desde OBS/vMix

- HTTP Live Streaming `(HLS)` - El soporte para el protocolo está muy extendido en reproductores multimedia, navegadores web, dispositivos móviles y servidores de transmisión de medios. (by Apple Inc.)

| Detalle             | value                                          |
| ------------------- | ---------------------------------------------- |
| Filename extension  | .m3u8                                          |
| Internet media type | application/vnd.apple.mpegurl or audio/mpegurl |
| Developed by        | Apple Inc.                                     |
| Initial release     | May 2009                                       |
| Extended from       | extended M3U                                   |
| Standard            | RFC 8216                                       |



# Requerimientos
Un servidor con ip publica con [Docker](https://www.docker.com/) instalado.
