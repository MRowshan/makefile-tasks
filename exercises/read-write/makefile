.PHONY = read write clear file

message = "insert message here"

read: write
	@cat test.txt

write: file
	@echo $(message) > test.txt

file: clear
	@touch test.txt

clear:
	@rm -f test.txt
