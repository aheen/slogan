slogan
======

slogan recruitment process for HDE

#include<stdio.h>
#include<float.h>
#include<math.h>
int main() {

float jumlah, rata2, kuadrat, bil1, bil2, kuadrat1, kuadrat2;

printf("enter first number =\n\n");

scanf("%f", &bil1);

printf("enter second number =\n\n");

scanf("%f", &bil2);

/*jumlah bilangan */

jumlah = bil1 + bil2;

/*rata2 bilangan */

rata2 = (bil1 + bil2)/2;

/*kuadrat bilangan*/

kuadrat1 = bil1*bil1;

kuadrat2 = bil2*bil2;

printf("sum of %f and %f is %f\n",bil1,bil2,jumlah);



printf("1st sum of squares from %f is %f\n",bil1,kuadrat1);

printf("2nd sum of squares from  %f is %f\n",bil2,kuadrat2);


}
