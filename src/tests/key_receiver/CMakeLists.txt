px4_add_module(
	MODULE tests__key_receiver
	MAIN key_receiver
	STACK_MAIN 2500
    	STACK_MAX 4000
	SRCS
		key_receiver.cpp
	DEPENDS
	)