check_PROGRAMS=ctest ftest
TESTS = $(check_PROGRAMS)
ctest_SOURCES = ctest.c
ftest_SOURCES = ftest.F90
ctest_LDADD = -L../ -lmpi-serial
ftest_LDADD = -L../ -lmpi-serial
