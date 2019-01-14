# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: vsteffen <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2019/01/14 20:50:00 by vsteffen          #+#    #+#              #
#    Updated: 2019/01/14 20:50:03 by vsteffen         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

obj-m += main.o

all:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules
	@echo "\033[32m.Hello World module build\033[0m"

clean:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean
	@echo "\033[32m.Hello World module clean\033[0m"
