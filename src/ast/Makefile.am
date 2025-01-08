# Name of the libaries
lib_LIBRARIES = libast.a

# List of file to compile in libast.a
libast_a_SOURCES =  \
  ast.c \
  ast.h

#specifies compiler and preprocessor flags for building the library :

#sets the preprocessor flags
libast_a_CPPFLAGS = -I$(top_srcdir)/src

#sets the compiler flags
libast_a_CFLAGS = -std=c99 -Werror -Wall -Wextra -Wvla -pedantic

#variable used to specify libraries
noinst_LIBRARIES = libast.a
