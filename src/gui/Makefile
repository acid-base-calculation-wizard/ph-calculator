all: lib-src/pHCalcFunc.c lib-src/pHCalc.h
	gcc -shared -o pHCalcFunc.dll lib-src/pHCalcFunc.c lib-src/pHCalc.h -lm

clean:
	rm -rf *.dll
