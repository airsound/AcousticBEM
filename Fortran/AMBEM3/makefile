AMBEM3: AMBEM3.o AMBEM3_T.o GEOM3D.o CGLS.o H3LC.o  INTEIG.o CGEIG.o
	gfortran -o AMBEM3 AMBEM3.o AMBEM3_T.o GEOM3D.o H3LC.o CGLS.o INTEIG.o CGEIG.o

AMBEM3.o: AMBEM3.FOR
	gfortran -c AMBEM3.FOR

AMBEM3_T.o: AMBEM3_T.FOR
	gfortran -c AMBEM3_T.FOR

GEOM3D.o: ../SHARED/GEOM3D.FOR
	gfortran -c ../SHARED/GEOM3D.FOR

H3LC.o: ../SHARED/H3LC.FOR
	gfortran -c ../SHARED/H3LC.FOR

CGLS.o: ../SHARED/CGLS.FOR
	gfortran -c ../SHARED/CGLS.FOR

INTEIG.o: ../SHARED/INTEIG.FOR
	gfortran -c ../SHARED/INTEIG.FOR

CGEIG.o: ../SHARED/CGEIG.FOR
	gfortran -c ../SHARED/CGEIG.FOR

clean:
	rm AMBEM3 AMBEM3.OUT AMBEM3.o AMBEM3_T.o GEOM3D.o H3LC.o CGLS.o  INTEIG.o CGEIG.o *~

