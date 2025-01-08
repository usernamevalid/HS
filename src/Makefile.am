#variable used to specify the subdirectories
SUBDIRS = ast \
      parser \
			lexer

#binary of the project
bin_PROGRAMS = 42sh

#specifies the source files for the program 
42sh_SOURCES = 42sh.c

# define preprocessor flags
42sh_CPPFLAGS = -I%D%

# define compiler flags
42sh_CFLAGS = -std=c99 -Werror -Wall -Wextra -Wvla -pedantic

#lists the dependencies the main program relies on during the linking phase
42sh_LDADD =  \
       ast/libast.a \
       parser/libparser.a \
       lexer/liblexer.a
