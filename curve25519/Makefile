

CURVE25519_FILES = \
api.h \
base.c \
fe.h \
fe_0.c \
fe_1.c \
fe_add.c \
fe_copy.c \
fe_cswap.c \
fe_frombytes.c \
fe_invert.c \
fe_mul.c \
fe_mul121666.c \
fe_sq.c \
fe_sub.c \
fe_tobytes.c \
montgomery.h \
pow225521.h \
pow225521.q \
scalarmult.c

CURVE25519_C_FILES = \
fe_0.c \
fe_1.c \
fe_add.c \
fe_copy.c \
fe_cswap.c \
fe_frombytes.c \
fe_invert.c \
fe_mul.c \
fe_mul121666.c \
fe_sq.c \
fe_sub.c \
fe_tobytes.c \
scalarmult.c


exe: $(CURVE25519_FILES)
	cc $(CURVE25519_C_FILES) -Iextra_includes/
