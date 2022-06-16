# CLAP4
Write a program in C, that asks from user to enter marks obtained in 5 subjects (out of 100) and find the percentage marks of student. The answer to this question is given below:

#include <stdio.h>

int main()

{

float Physics,Chemistry,Maths,CS,English;

float sum,average;

/* Input marks for all five subjects of student */

printf("Enter marks for all five subjects: \n");

scanf("%f%f%f%f%f",&Physics,&Chemistry,&Maths,&CS,&English);

/* Calculate sum and average */

sum = Physics+Chemistry+Maths+CS+English;

average = sum/(float)5;
printf("Percentage marks = %.2f", average);

return 0;
}
