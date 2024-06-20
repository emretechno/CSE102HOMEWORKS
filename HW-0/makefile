all: clean compile run

compile: main.c util.c util.h
	@printf "============================================\n"
	@printf "The Program Is Compiling...\n"
	@printf "============================================\n"
	@gcc -o Emre main.c util.c

run:
	@printf "The Program Is Running...\n"
	@printf "⋘ L𝑜ading  Data...⋙\n"
	./Emre
	@printf "\n===========================================\n"
	@printf "The Compiling Is Done.Yusuf Emre Kilicer."

clean:
	@printf "============================================\n"
	@printf "The compiled files were cleaned.\n"
	@printf "See You Again...\n"
	@printf "============================================\n"
	@rm -f Emre
	@rm -f *.o

