# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: tpetros <tpetros@student.42abudhabi.ae>    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2023/09/22 15:19:46 by tpetros           #+#    #+#              #
#    Updated: 2023/09/22 16:10:32 by tpetros          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = account

SRC = Account.cpp tests.cpp

CC = c++
RM = rm -rf

CPPFLAGS = -Wall -Werror -Wextra -std=c++98

OBJS = $(SRC:.cpp=.o)

$(NAME): $(OBJS)
	$(CC) $(CPPFLAGS) $(OBJS) -o $(NAME)

all: $(NAME)

clean:
	$(RM) $(OBJS)

fclean: clean
	$(RM) $(NAME)

re: fclean all