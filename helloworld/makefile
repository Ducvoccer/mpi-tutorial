EXECS=mpi_hello_world
MPICC?=mpicc

all: ${EXECS}

mpi_hello_world: helloworld.c
	${MPICC} -o mpi_hello_world helloworld.c

clean:
	rm -f ${EXECS}