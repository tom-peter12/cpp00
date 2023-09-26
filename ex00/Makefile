# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: tpetros <tpetros@student.42abudhabi.ae>    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2023/09/17 18:43:46 by tpetros           #+#    #+#              #
#    Updated: 2023/09/25 16:29:55 by tpetros          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = megaphone

SRC = megaphone.cpp

CC = c++
RM = rm -rf

CPPFLAGS = -Wall -Werror -Wextra -std=c++98

OBJS = $(SRC:.cpp=.o)

${NAME}: ${OBJS}
	$(CC) $(CPPFLAGS) $(OBJS) -o ${NAME}

all: ${NAME}

clean:
	$(RM) $(OBJS)

fclean: clean
	$(RM) $(NAME)

re:	fclean all
