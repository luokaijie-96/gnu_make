
.PHONY: test

ifeq ($(MAKELEVEL),0)
all:msg
else
all:test
endif

test:
	@echo "subdir makelevel = $(MAKELEVEL)"

msg:
	@echo "Can not make in this directory!"
