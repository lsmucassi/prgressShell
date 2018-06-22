# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: lmucassi <lmucassi@student.42.fr>          +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/06/10 11:45:14 by lmucassi          #+#    #+#              #
#    Updated: 2018/06/22 11:57:18 by lmucassi         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME	=	ft_didit

COMP	=	clang++

FLAG	=	-Wall -Wextra -Werror

#EXT_LIB	=	-lcurses

SRC_DIR	=	./src/

SRC		=	main.cpp

#CLASS	=	this.cpp\
		
$(NAME): 
	@echo	"\033[32m\nCreating AbtractVM PROJECT\n\n \033[00m"
	@echo	"\033[32mAUTHOR	\t:	\tLMUCASSI \033[00m"
	@echo	"\033[32mPROJECT	\t:	\tAbtractVM \033[00m"
	@echo	"\033[32mMODULE	\t:	\tCPP \033[00m"
	@echo	"\033[32mSCHOOL	\t:	\tWETHINKCODE_ [JHB]\n\n \033[00m"
	@$(COMP) $(FLAG)  $(SRC) -o $(NAME)
	@sh progB.sh 10
	@echo	"\033[32m\nFinishing Compilation \033[00m"
	@echo	"\033[32mDONE ! \033[00m"

clean:
	@echo	"\033[32mCleaning Project \033[00m"
	@rm	 $(NAME)
	@echo	"\033[32mDONE ! \033[00m"

fclean: clean

re:	fclean

.PHONY: re clean fclean
