# makeplus
Reusable Makefile set for C++

## Usage
	~/makeplus $ make        // Build. The executable and .o files are in the posix_out directory.
	~/makeplus $ make clean  // Erase posix_out directory.
	                         // Executable, .o files, and dependency file will be deleted.
	~/makeplus $ make dep    // Revise dependency. The file is in the posix_out directory.
