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

 * [caml-dypgen][] 20110328-1

[caml-dypgen]: http://dypgen.free.fr/

MacPorts
--------

http://www.macports.org/

OCaml
-----

http://www.ocaml.org/
