TARGETS = spark
CFLAGS =  -lrt
CC = c++

all: $(TARGETS)

cm1: cm1.c spark.c
	$(CC) $(CFLAGS) spark.c -o $(TARGETS)

clean:
	rm -f $(TARGETS) *.o *.stderr *.stdout core *~
	rm *.out *.dat
	touch spark_plot.dat
