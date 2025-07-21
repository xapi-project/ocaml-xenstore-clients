# v1.5.0 (21-Jul-2025)
* Remove usage of deprecated 'restrict'

# v1.4.0 (9-Apr-2025)
* Use ounit2
* Split lwt code to a different package

# v1.3.0 (19-Jan-2021)
* Update CI
* Bring back META template

# v1.2.0 (10-Jan-2021)
* Use dune in Makefile
* Fix license in opam metadata

# v1.1.0 (18-Jun-2019):
* Upgrade build to dune from jbuilder (@avsm)
* Test OCaml 4.07 in CI (@avsm)
* Upgrade opam metadata to 2.0 format (@avsm)

# v1.0.0 (07-Dec-2017):
* compile with -safe-string

# 0.9.6 (12-Jun-2017):
* add backwards-compat ocamlfind packages
  - xenstore_transport.unix
  - xenstore_transport.lwt

# 0.9.5 (12-Jun-2017):
* unix: search for the xenbus path
* add more test cases
* remove camlp4 dependency
* build with jbuilder
* travis: use a modern Docker-based setup

# 0.9.4 (16-Jun-2014):
* use the xenbus device if the Unix domain socket isn't available
* respect the XENSTORED_PATH environment variable

# 0.9.3 (9-May-2014):
* fix a file descriptor leak when we cannot connect to xenstore

# 0.9.2 (27-Aug-2013):
* adapt to new xenstore signature which makes it easy to write code
  oblivious to whether it's running in Unix userspace or xen

# 0.9.1 (6-Aug-2013):
* update to xenstore 1.2.3

# 0.9.0 (3-Jun-2013):
* first public release

