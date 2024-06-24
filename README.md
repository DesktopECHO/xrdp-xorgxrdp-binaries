`````xrdp 0.10.80
  A Remote Desktop Protocol Server.
  Copyright (C) 2004-2024 Jay Sorg, Neutrino Labs, and all contributors.
  See https://github.com/neutrinolabs/xrdp for more information.

  Configure options:
      --enable-ibus
      --enable-x264
      --enable-fdkaac
      --enable-rdpsndaudin
      --enable-pixman
      --enable-ipv6
      --enable-jpeg
      --enable-fuse
      --enable-rfxcodec
      --enable-opus
      --enable-painter
      --enable-vsock
      --build=x86_64-linux-gnu
      --prefix=/usr
      --includedir=${prefix}/include
      --mandir=${prefix}/share/man
      --infodir=${prefix}/share/info
      --sysconfdir=/etc
      --localstatedir=/var
      --disable-silent-rules
      --libdir=${prefix}/lib/x86_64-linux-gnu
      --libexecdir=${prefix}/lib/x86_64-linux-gnu
      --disable-maintainer-mode
      --disable-dependency-tracking
      --with-socketdir=/run/xrdp/sockdir
      --with-imlib2
      build_alias=x86_64-linux-gnu
      CFLAGS=-g -O2 -ffile-prefix-map=/home/zero/xrdp-xorgxrdp/xrdp=. -flto=auto -ffat-lto-objects -flto=auto -ffat-lto-objects -fstack-protector-strong -Wformat -Werror=format-security 
      LDFLAGS=-Wl,-Bsymbolic-functions -flto=auto -ffat-lto-objects -flto=auto -Wl,-z,relro -Wl,-z,now -Wl,--as-needed
      CPPFLAGS=-Wdate-time -D_FORTIFY_SOURCE=2 
      CXXFLAGS=-g -O2 -ffile-prefix-map=/home/zero/xrdp-xorgxrdp/xrdp=. -flto=auto -ffat-lto-objects -flto=auto -ffat-lto-objects -fstack-protector-strong -Wformat -Werror=format-security
      PKG_CONFIG_PATH=/home/zero/xrdp-xorgxrdp/xrdp/pkgconfig

`````
