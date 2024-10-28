# Target executable name
TARGET = binaryConverter

# Source files
SRCS = binaryconverter.cpp

# Compiler and flags
CXX = g++
CXXFLAGS = -std=c++11 -Wall -Wextra -O2

# Default target
all: $(TARGET)

# Build the executable
$(TARGET): $(SRCS)
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(SRCS)

# Clean up the build
clean:
	rm -f $(TARGET)
