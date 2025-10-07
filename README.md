# c-program
 Read and Display Elements of 1-D Array 
 #include <stdio.h> 
int main() { 
int arr[5], i; 
printf("Enter 5 integers:\n"); 
for(i = 0; i < 5; i++) { 
scanf("%d", &arr[i]); 
} 
printf("Array elements are:\n"); 
for(i = 0; i < 5; i++) { 
printf("%d ", arr[i]); 
} 
return 0; 
}
