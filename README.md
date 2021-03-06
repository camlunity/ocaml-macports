OCaml-related MacPorts
======================

Installing
----------

#### Clone the repository somewhere:

    $ cd ~/work
    $ git clone git://github.com/camlunity/ocaml-macports.git

#### Open the sources.conf file in a text editor:

    $ open -e /opt/local/etc/macports/sources.conf

#### Insert an URL pointing to the ocaml-ports directory *before* the rsync URL as shown:

    file:///Users/xavier/work/ocaml-macports
    rsync://rsync.macports.org/release/ports [default]

#### Install caml-findlib

    $ sudo port install caml-findlib

Available portfiles
-------------------

 * [caml-batteries][] 1.4.1
 * [caml-bin-prot][] 1.3.1
 * [caml-camomile][] 0.8.3
 * [caml-dypgen][] 20110618-1
 * [caml-iteratees][] 0.3
 * [caml-lwt][] 2.3.1
 * [caml-objsize][] 0.16
 * [caml-ocamlnet][] 3.4.1
 * [caml-ounit][] 1.1.0
 * [caml-postgresql][] 1.16.0
 * [caml-react][] 0.9.2
 * [caml-sqlite3][] 1.6.1
 * [caml-ssl][] 0.4.6
 * [caml-text][] 0.5
 * [caml-xmlm][] 1.0.2
 * [ocaml][] 3.12.1
 * [ocaml-faad][] 0.3.0
 * [ocaml-flac][] 0.1.0
 * [ocaml-lame][] 0.3.1
 * [ocaml-lastfm][] 0.3.0
 * [ocaml-mad][] 0.4.4
 * [ocaml-ogg][] 0.4.3
 * [ocaml-speex][] 0.2.0
 * [ocaml-taglib][] 0.2.0
 * [ocaml-theora][] 0.3.0
 * [ocaml-vorbis][] 0.6.1
 * [ocaml-xmlplaylist][] 0.1.3
 * [ocamlsdl][] 0.8.0

[caml-batteries]: https://github.com/ocaml-batteries-team/batteries-included/
[caml-bin-prot]: http://ocaml.janestreet.com/?q=node/13
[caml-camomile]: http://camomile.sourceforge.net/
[caml-dypgen]: http://dypgen.free.fr/
[caml-iteratees]: http://ocaml-iteratees.forge.ocamlcore.org/
[caml-lwt]: http://ocsigen.org/lwt
[caml-objsize]: http://forge.ocamlcore.org/projects/objsize/
[caml-ocamlnet]: http://projects.camlcity.org/projects/ocamlnet.html
[caml-ounit]: http://ounit.forge.ocamlcore.org/
[caml-postgresql]: http://www.ocaml.info/home/ocaml_sources.html
[caml-react]: http://erratique.ch/software/react
[caml-sqlite3]: http://www.ocaml.info/home/ocaml_sources.html
[caml-ssl]: http://savonet.sf.net
[caml-text]: http://ocaml-text.forge.ocamlcore.org/
[caml-xmlm]: http://erratique.ch/software/xmlm
[ocaml]: http://caml.inria.fr/ocaml/
[ocaml-faad]: http://savonet.sf.net
[ocaml-flac]: http://savonet.sf.net
[ocaml-lame]: http://savonet.sf.net
[ocaml-lastfm]: http://savonet.sf.net
[ocaml-mad]: http://savonet.sf.net
[ocaml-ogg]: http://savonet.sf.net
[ocaml-speex]: http://savonet.sf.net
[ocaml-taglib]: http://savonet.sf.net
[ocaml-theora]: http://savonet.sf.net
[ocaml-vorbis]: http://savonet.sf.net
[ocaml-xmlplaylist]: http://savonet.sf.net
[ocamlsdl]: http://ocamlsdl.sourceforge.net/home.html

MacPorts
--------

http://www.macports.org/

OCaml
-----

http://www.ocaml.org/
