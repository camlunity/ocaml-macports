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

    $ file:///Users/xavier/work/ocaml-macports
    $ rsync://rsync.macports.org/release/ports [default]

Available portfiles
-------------------

 * [caml-camomile][] 0.8.3
 * [caml-dypgen][] 20110328-1
 * [caml-iteratees][] 0.3
 * [caml-lwt][] 2.3.0
 * [caml-objsize][] 0.16
 * [caml-postgresql][] 1.16.0
 * [caml-react][] 0.9.2
 * [caml-sqlite3][] 1.6.1
 * [caml-ssl][] 0.4.5
 * [caml-text][] 0.4
 * [caml-xmlm][] 1.0.2
 * [ocaml-ogg][] 0.4.1
 * [ocaml-vorbis][] 0.5.1
 * [ocaml-xmlplaylist][] 0.1.2

[caml-camomile]: http://camomile.sourceforge.net/
[caml-dypgen]: http://dypgen.free.fr/
[caml-iteratees]: http://ocaml-iteratees.forge.ocamlcore.org/
[caml-lwt]: http://ocsigen.org/lwt
[caml-objsize]: http://forge.ocamlcore.org/projects/objsize/
[caml-postgresql]: http://www.ocaml.info/home/ocaml_sources.html
[caml-react]: http://erratique.ch/software/react
[caml-sqlite3]: http://www.ocaml.info/home/ocaml_sources.html
[caml-ssl]: http://savonet.sf.net
[caml-text]: http://ocaml-text.forge.ocamlcore.org/
[caml-xmlm]: http://erratique.ch/software/xmlm
[ocaml-ogg]: http://savonet.sf.net
[ocaml-vorbis]: http://savonet.sf.net
[ocaml-xmlplaylist]: http://savonet.sf.net

MacPorts
--------

http://www.macports.org/

OCaml
-----

http://www.ocaml.org/
