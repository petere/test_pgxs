MODULES = test1 test2
DATA_built = test.sql

EXTRA_CLEAN = test2.c

PG_CONFIG = pg_config
PGXS = $(shell $(PG_CONFIG) --pgxs)
include $(PGXS)

test2.c: test1.c
	cp $< $@

%: %.in
	cp $< $@
