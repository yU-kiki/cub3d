CC = gcc
CFLAGS = -Wall -Wextra -Werror

$(NAME): $(OBJ)
	$(CC) -Lmlx -lmlx -framework OpenGL -framework AppKit -o $(NAME)

%.o: %.c
	$(CC) $(CFLAGS) -Imlx -c $< -o $@

