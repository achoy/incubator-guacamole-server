
# How to make configure work

## Prerequisites

- auto tools

## Steps

See http://www.ifnamemain.com/posts/2014/Mar/13/autoconf_automake/ for more info

### System checks

` $ autoscan `

` $ autoheader `

` $ autoconf `

### Build (automake)

` $ libtoolize `

` $ aclocal `

` $ automake --add-missing `

### Now finally configure

` $ ./configure --with-init-dir=/etc/init.d `

