SRCS	= main.cpp
OBJS	= $(SRCS:.cpp=.o)

CXX	= clang++
CXXFLAGS	= -Wall -Wextra -Werror -std=c++98

NAME	= replace

all: $(NAME)

$(NAME): $(OBJS)
	$(CXX) $(CXXFLAGS) $(OBJS) -o $(NAME)

clean:
	rm -f $(OBJS)

fclean: clean
	rm -f $(NAME)

re: fclean all

.PHONY: all clean fclean re