# Copyright 2004 Karl Trygve Kalleberg <karltk@gentoo.org>
# Copyright 2004 Gentoo Foundation
# Distributed under the terms of the GNU General Public License v2

include ../../makedefs.mak

.PHONY: all clean dist
all:

dist:
	mkdir -p ../../$(DISTDIR)/src/ekeyword
	cp Makefile AUTHORS README ekeyword.py ekeyword_unittest.py \
		../../$(DISTDIR)/src/ekeyword/

install: all
	install -m 0755 ekeyword.py $(BINDIR)/ekeyword
	install -d $(DOCDIR)/ekeyword
	install -m 0644 AUTHORS README $(DOCDIR)/ekeyword/
