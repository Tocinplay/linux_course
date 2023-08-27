override file_name := main
file_suffix := .c
file_need := ${file_name}${file_suffix}

file_need += cal.c

main:main.o cal.o
	echo file_need is $(file_need) 
	gcc $(file_need) -o main
clean:
	rm -rf *.i *.s *.o main