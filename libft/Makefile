# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: ythollet <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2017/11/13 13:26:15 by ythollet          #+#    #+#              #
#    Updated: 2017/11/22 16:23:51 by ythollet         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

CC = gcc
CFLAGS = -c -Wall -Wextra -Werror
NAME = libft.a
SRCS = 	ft_isdigit.c \
		ft_memchr.c  \
		ft_putchar.c  \
		ft_putstr.c \
		ft_strcpy.c \
		ft_strjoin.c \
		ft_strncmp.c \
		ft_strsplit.c \
		ft_atoi.c \
		ft_isprint.c \
		ft_memcmp.c \
		ft_putchar_fd.c \
		ft_putstr_fd.c \
		ft_strdel.c \
		ft_strlcat.c \
		ft_strncpy.c \
		ft_strstr.c \
		ft_bzero.c \
		ft_itoa.c \
		ft_memcpy.c \
		ft_putendl.c \
		ft_strcat.c \
		ft_strdup.c \
		ft_strlen.c \
		ft_strnequ.c \
		ft_strsub.c \
		ft_isupper.c\
		ft_isalnum.c \
		ft_lenint.c \
		ft_memdel.c \
		ft_putendl_fd.c \
		ft_strchr.c \
		ft_strequ.c \
		ft_strmap.c \
		ft_strnew.c \
		ft_strtrim.c \
		ft_islower.c \
		ft_isalpha.c \
		ft_memalloc.c \
		ft_memmove.c \
		ft_putnbr.c \
		ft_strclr.c \
		ft_striter.c \
		ft_strmapi.c \
		ft_strnstr.c \
		ft_tolower.c \
		ft_isspace.c \
		ft_isascii.c \
		ft_memccpy.c \
		ft_memset.c \
		ft_putnbr_fd.c \
		ft_strcmp.c \
		ft_striteri.c \
		ft_strncat.c \
		ft_strrchr.c \
		ft_toupper.c \
		ft_lstnew.c \
		ft_lstdelone.c \
		ft_lstdel.c \
		ft_lstadd.c \
		ft_lstiter.c \
		ft_split_whitespaces.c \
		ft_sqrt.c \
		ft_nbrchar.c \
		ft_strmcat.c

OBJ = $(SRCS:.c=.o)

all:$(NAME)

$(NAME):
	$(CC) $(CFLAGS) $(SRCS)
	ar rc $(NAME) $(OBJ)
	ranlib $(NAME)

clean:
	/bin/rm -f *.o

fclean: clean
	/bin/rm -f $(NAME)

re: fclean all

.PHONY: clean fclean re