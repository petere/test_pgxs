PROGRAM = testprog
OBJS = testprog.o

SCRIPTS_built = script1
SCRIPTS = script2

%: %.in
	cp $< $@
	chmod a+x $@

PG_CONFIG = pg_config
PGXS = $(shell $(PG_CONFIG) --pgxs)
include $(PGXS)
