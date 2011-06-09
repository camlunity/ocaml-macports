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
 * [caml-objsize][] 0.16
 * [caml-postgresql][] 1.16.0
 * [caml-react][] 0.9.2
 * [caml-sqlite3][] 1.6.1

[caml-camomile]: http://camomile.sourceforge.net/
[caml-dypgen]: http://dypgen.free.fr/
[caml-objsize]: http://forge.ocamlcore.org/projects/objsize/
[caml-postgresql]: http://www.ocaml.info/home/ocaml_sources.html
[caml-react]: http://erratique.ch/software/react
[caml-sqlite3]: http://www.ocaml.info/home/ocaml_sources.html

MacPorts
--------

http://www.macports.org/

OCaml
-----

http://www.ocaml.org/
