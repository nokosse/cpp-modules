NAME = megaphone
CC = c++
FLAGS = -Wall -Wextra -Werror -std=c++98
RM = rm -rf
all: $(NAME)
$(NAME): $(NAME).cpp
	$(CC) $(FLAGS) megaphone.cpp -o $(NAME)
clean:
	$(RM) $(NAME)
fclean: clean
	$(RM) $(NAME)
re: fclean
.PHONY: all clean re