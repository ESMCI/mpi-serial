lib_LIBRARIES = libmpi-serial.a
libmpi_serial_a_SOURCES=fort.F90 mpif.F90 mpi.c send.c recv.c collective.c req.c collective.c  \
			req.c list.c handles.c comm.c error.c ic_merge.c group.c time.c pack.c \
			type.c type_const.c copy.c op.c cart.c getcount.c probe.c info.c
mpi_serial_includedir = $(prefix)/include
mpi_serial_include_HEADERS = mpi.h mpif.h mpi.mod

SUBDIRS = . tests
