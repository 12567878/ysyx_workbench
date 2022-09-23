all:
	@echo "Write this Makefile by your self."

sim:
	verilator -Wall --cc --exe --build --trace csrc/main.cpp vsrc/top.v
	$(call git_commit, "sim RTL") # DO NOT REMOVE THIS LINE!!!
	@echo "Write this Makefile by your self."


include ../Makefile
