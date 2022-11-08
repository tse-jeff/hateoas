LINTER = flake8
<<<<<<< HEAD
COVER_PKG = $(shell pwd)
=======
PYTESTFLAGS = -vv --verbose --tb=short
>>>>>>> template/master

FORCE:

docs: $(DOCFILES)

<<<<<<< HEAD
=======
%.py: FORCE
	pytest -s tests/test_$*.py

>>>>>>> template/master
%.html: %.py
	pydoc3 -w ./$<
	git add $@

tests: lint unit

unit: FORCE
<<<<<<< HEAD
	nosetests --exe --verbose --with-coverage --cover-package=$(COVER_PKG)
=======
	pytest $(PYTESTFLAGS)
>>>>>>> template/master

lint: FORCE
	$(LINTER) *.py
