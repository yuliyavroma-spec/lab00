# Отчет

## Проверка среды разработки

```shell
$ cmake --version

cmake version 3.31.6

CMake suite maintained and supported by Kitware (kitware. com/cmake).

$ curl --version 
curl 8.14. 1 (x86_64-pc-linux-gnu) libcurl/8. 14. 1 OpenSSL/3.5.4 zlib/1.3.1 brotli/1.1.0 zstd/1.5.7 libidn2/2.3.8 libpsl/0.21.2 libssh2/1.11.1 nghttp2/1.64.0 nghttp3/1.8.0 librtmp/2.3 OpenLDAP/2.6.10
Release-Date: 2025-06-04, security patched: 8. 14. 1-2+deb13u2
Protocols: dict file ftp ftps gopher gophers http https imap imaps ipfs ipns ldap ldaps mqtt pop3 pop3s rtmp rtsp scp sftp smb smbs smtp smtps telnet tftp ws wss
Features: alt-svc AsynchDNS brotli GSS-API HSTS HTTP2 HTTP3 HTTPS-proxy IDN IPv6 Kerberos Largefile libz NTLM PSL SPNEGO SSL threadsafe TLS-SRP UnixSockets zstd

$ git --version
git version 2.47.3

$ g++ --version
g++ (Debian 14.2.0-19) 14.2.0

$ make --version
GNU Make 4.4.1

$ tree --version
tree v2.2.1 @ 1996 - 2024 by Steve Baker, Thomas Moore, Francesc Rocher, Florian Sesser, Kyosuke Tokoro

$ wget --version
GNU Wget 1.25.0 для linux-gnu.
-cares +digest -gpgme +https +ipv6 +iri +large-file -metalink +nls
+ntlm +opie +psl +ssl/gnutls
Wgetrc:
/etc/wgetrc (CncTeMa)
Локаль:
/usr/share/locale
Компиляция :
gcc -DHAVE_CONFIG H -DSYSTEM WGETRC="/etc/wgetrc"
-DLOCALEDIR="/usr/share/locale" -I. -I .. / .. /src -I .. /lib
-I .. / .. /lib -Wdate-time -D FORTIFY SOURCE=2
- I/usr/include/p11-kit-1 -DHAVE_LIBGNUTLS -DNDEBUG -g -02
-Werror=implicit - function-declaration
- ffile-prefix-map=/build/reproducible-path/wget-1.25.0 =.
- fstack-protector- strong - fstack-clash-protection -Wformat
-Werror=format - security -fcf-protection -DNO_SSLv2
Ссылка:
gcc -I/usr/include/p11-kit-1 -DHAVE_LIBGNUTLS -DNDEBUG -g -02
-Werror=implicit - function-declaration
-ffile-prefix-map=/build/reproducible-path/wget -1.25.0 =.
- fstack-protector-strong - fstack-clash-protection -Wformat
-Werror=format - security -fcf-protection -DNO_SSLv2 -Wl, -z, relro
-Wl, -z, now -lpcre2-8 -luuid -lidn2 -lnettle -lgnutls -lz -lpsl
.. /lib/libgnu. a

$ openssl version
OpenSSL 3.5.4 30_Sep 2025 (Library: OpenSSL 3.5.4 30 Sep 2025)