# CLAP4
𝐖𝐫𝐢𝐭𝐞 𝐚 𝐩𝐫𝐨𝐠𝐫𝐚𝐦 𝐢𝐧 𝐂, 𝐭𝐡𝐚𝐭 𝐚𝐬𝐤𝐬 𝐟𝐫𝐨𝐦 𝐮𝐬𝐞𝐫 𝐭𝐨 𝐞𝐧𝐭𝐞𝐫 𝐦𝐚𝐫𝐤𝐬 𝐨𝐛𝐭𝐚𝐢𝐧𝐞𝐝 𝐢𝐧 𝟓 𝐬𝐮𝐛𝐣𝐞𝐜𝐭𝐬 (𝐨𝐮𝐭 𝐨𝐟 𝟏𝟎𝟎) 𝐚𝐧𝐝 𝐟𝐢𝐧𝐝 𝐭𝐡𝐞 𝐩𝐞𝐫𝐜𝐞𝐧𝐭𝐚𝐠𝐞 𝐦𝐚𝐫𝐤𝐬 𝐨𝐟 𝐬𝐭𝐮𝐝𝐞𝐧𝐭. 𝐓𝐡𝐞 𝐚𝐧𝐬𝐰𝐞𝐫 𝐭𝐨 𝐭𝐡𝐢𝐬 𝐪𝐮𝐞𝐬𝐭𝐢𝐨𝐧 𝐢𝐬 𝐠𝐢𝐯𝐞𝐧 𝐛𝐞𝐥𝐨𝐰:

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
