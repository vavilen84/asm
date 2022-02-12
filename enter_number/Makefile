all:
	@rm enter_number ||:
	nasm -f elf enter_number.asm
	ld -m elf_i386 -s -o enter_number enter_number.o
	rm enter_number.o
