# xdrum/docker-nginx-extras
Nginx extended version: provides a version of nginx with the standard modules, plus extra features and modules,
this container is based on ubuntu:14.04 (trusty) and the PPA nginx/stable.

STANDARD HTTP MODULES: Core, Access, Auth Basic, Auto Index, Browser,
Charset, Empty GIF, FastCGI, Geo, Gzip, Headers, Index, Limit Requests,
Limit Zone, Log, Map, Memcached, Proxy, Referer, Rewrite, SCGI,
Split Clients, SSI, Upstream, User ID, UWSGI.

OPTIONAL HTTP MODULES: Addition, Debug, Embedded Perl, FLV, GeoIP,
Gzip Precompression, Image Filter, IPv6, MP4, Random Index, Real IP,
Secure Link, Spdy, SSL, Stub Status, Substitution, WebDAV, XSLT.

MAIL MODULES: Mail Core, IMAP, POP3, SMTP, SSL.

THIRD PARTY MODULES: Auth PAM, Chunkin, DAV Ext, Echo, Embedded Lua,
Fancy Index, HttpHeadersMore, HTTP Substitution Filter, http push,
Nginx Development Kit, Upload Progress, Upstream Fair Queue.

## Usage

```bash
$ docker run -ti --rm -v /path/to/nginx:/etc/nginx -p 8080:80 xdrum/nginx-extras
```
