# Variables
SRC_DIR = src/main/java
OUT_DIR = out

# Default target
all: compile run

# Compile Java files
compile:
	@mkdir -p $(OUT_DIR)
	javac $(SRC_DIR)/*.java -d $(OUT_DIR)

# Run the program
run:
	java -cp $(OUT_DIR) Main

# Clean up compiled files
clean:
	rm -rf $(OUT_DIR)
