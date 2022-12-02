posibles problemas:
	Posible tamaño maximo para las macros. En el subject pone, "se compilara de esta forma: ... -D BUFFER_SIZE=xx ..." el que solo indique dos digitos puede significar que haya un maximo para el tamaño de las macros, tener cuidado con eso
	Usar como variable estatica una estructura que asocie a cada fd un buffer con lo que se haya leido de ese fd
