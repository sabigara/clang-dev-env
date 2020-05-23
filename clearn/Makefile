PROGRAM = include	
OBJS		=	main.o
SRCS		= $(OBJS:%.o=%.c)
CC			= gcc
CFLAGS	=	-g -Wall
LDFRAGS =

$(PROGRAM):$(OBJS)
		$(CC) $(CFLAGS) $(LDFRAGS) -o $(PROGRAM) $(OBJS) $(LDLIBS)