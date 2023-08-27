use_override = anything
file_name := $(if $(use_override),main,err_name)
file_suffix := .c
file_need := ${file_name}${file_suffix}

#file_need += cal.c
title_cal = cal
new_file = $(1)$(2)
file_need += $(call new_file,$(title_cal),$(file_suffix))

main:main.o cal.o
	echo file_need is $(file_need) 
	gcc $(file_need) -o main
clean:
	rm -rf *.i *.s *.o main