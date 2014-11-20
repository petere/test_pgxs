MODULE_big = testext
OBJS = testext.o
EXTENSION = testext
DOCS = README
DATA_TSEARCH = testext.rules
DATA = testext--0.sql testext--unpackaged.sql
REGRESS = test1 test2

PG_CONFIG = pg_config
PGXS = $(shell $(PG_CONFIG) --pgxs)
include $(PGXS)
