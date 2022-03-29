saxpyModule.cuf - module for "saxpy" transformation, i.e. y -> y + a*x
where a is constant

saxpyMain.cuf - programm for saxpy that for given a and x(N=128*1024*1024) = 1
and y(N) = 2 uses saxpymodule

saxpyMain1.cuf - programm for saxpy that for given a and x(i) = i
and y(i) = i, i=1...N uses saxpymodule