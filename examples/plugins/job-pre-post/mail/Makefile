# Glue for base avocado/Makefile
#

DESTDIR=/
PYTHON=$(shell which python)

link:
	$(PYTHON) setup.py develop --user
unlink:
	$(PYTHON) setup.py develop --uninstall --user
install:
	$(PYTHON) setup.py install --root $(DESTDIR)
