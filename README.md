#include <stdio.h>
int main () {
	int year_of_birth,age,corrent_year;
    printf ("I would like you to give me your birth time: ");
    scanf ("%d",&year_of_birth);
    printf("Give your corrent year: ");
    scanf("%d",&corrent_year);
    age=corrent_year-year_of_birth;
    
    if(age >=6 && age <=18) {
    printf("You go to school.\nAnd you are young");
	} 
	else if(age >=19 && age <=35) {
	printf("You are a student\nAnd you are young");
	} 
	else if(age >=36 && age <=60){
	printf("You are working\nYou're middle age");
	} 
	else if(age >= 61){
	printf("\nYou are old");
}
	printf("\nYour age is: %d\n",age);
	return 0;
}
   
