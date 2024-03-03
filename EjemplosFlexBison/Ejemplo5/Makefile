# part of the makefile
fb1-5: fb1-5.l SimpleCalculatorFb1-5.y
	bison -d SimpleCalculatorFb1-5.y
	flex fb1-5.l
	cc -o $@ SimpleCalculatorFb1-5.tab.c lex.yy.c -lfl
