file_name := main cal
file_suffix := .c
file_need := $(foreach n,$(file_name),$(n)$(file_suffix))

main:main.o cal.o
	echo file_need is $(file_need) 
	gcc $(file_need) -o main
clean:
	rm -rf *.i *.s *.o main