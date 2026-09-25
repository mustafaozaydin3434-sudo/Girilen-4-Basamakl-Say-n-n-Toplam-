# Girilen-4-Basamakl-Say-n-n-Toplam-
C dili ile yazılan Girilen 4 Basamaklı Sayının Toplamı


#include <stdio.h>

int main()
{
    int number, thousands_place, hundreds_digit, tens_diigit, ones_digit, sum;

    sum = 0;

    printf("Enter a number: ");
    scanf_s("%d", &number);

    thousands_place = number / 1000;
    hundreds_digit = (number / 100) % 10;
    tens_diigit = (number / 10) % 10;
    ones_digit = number % 10;

    sum = thousands_place + hundreds_digit + tens_diigit + ones_digit;

    printf("the sum of the digits of the number you entered: %d", sum);

    return 0;

};
