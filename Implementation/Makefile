PROJECT_NAME = Bank

# Output directory
BUILD = build

# All source code files
SRC = main.c\
ifdef OS
   EXEC = exe
else
   ifeq ($(shell uname), Linux)
   EXEC = out
endif
endif

TEST_OUTPUT = $(BUILD)/Test_$(PROJECT_NAME).$(EXEC)

# All include folders with header files
INC	= -Iinc\
#Library Inlcudes
#INCLUDE_LIBS = 
INCLUDE_LIBS = -lcunit

# Project Output name
PROJECT_OUTPUT = $(BUILD)/$(PROJECT_NAME).$(EXEC)

# Document files
DOCUMENTATION_OUTPUT = documentation/html

# Default target built
$(PROJECT_NAME):all

# Run the target even if the matching name exists
.PHONY: run clean test doc all

all: $(SRC) $(BUILD)
	gcc $(SRC) $(INC) -o $(PROJECT_OUTPUT) -lm

# Call `make run` to run the application
run:$(PROJECT_NAME)
	./$(PROJECT_OUTPUT)
doc:
	make -C ./documentation
 
