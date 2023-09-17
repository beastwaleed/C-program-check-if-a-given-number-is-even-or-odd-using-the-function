# C-program-check-if-a-given-number-is-even-or-odd-using-the-function
A program in C to Check the given number is even or odd
Code ---->

#include <stdio.h>

// Function prototype for the odd function
int odd(int);

int main() {
    int number;

    // Prompt the user to enter a value
    printf("Enter your value = ");

    // Read the input value from the user
    scanf("%d", &number);

    // Call the odd function to check if the number is odd or even
    odd(number);

    return 0;
}

// Function to determine if a number is odd or even
int odd(int number) {
    // Check if the number is divisible by 3 to determine oddness
    if (number % 3 == 0) {
        printf("The given number is Odd\n");
    } else {
        printf("The given number is even\n");
    }

    return 0; // The return value here is not necessary, but it's included for consistency
}

// Github: Beastwaleed
