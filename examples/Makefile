
all: pipe1 pipe2 shm_create shm_attach shm_delete signals_ex sigchld

clean:
	rm -f pipe1 pipe2 shm_create shm_attach shm_delete signals_ex sigchld

pipe1: pipe1.c
	gcc -o pipe1 pipe1.c -Wall

pipe2: pipe2.c
	gcc -o pipe2 pipe2.c -Wall

shm_create: shm_create.c
	gcc -o shm_create shm_create.c -Wall

shm_attach: shm_attach.c
	gcc -o shm_attach shm_attach.c -Wall

shm_delete: shm_delete.c
	gcc -o shm_delete shm_delete.c -Wall

signals_ex: signals_ex.c
	gcc -o signals_ex signals_ex.c -Wall

sigchld: sigchld.c
	gcc -o sigchld sigchld.c -Wall
