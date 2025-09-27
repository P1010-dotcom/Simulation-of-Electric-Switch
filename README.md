#include <stdio.h>
int main() {
int door;
printf("Enter door status (1 = Open, 0 = Closed): ");
scanf("%d", &door);
if (door == 1) {
printf("Light is ON.\n");
} else if (door == 0) {
printf("Light is OFF.\n");
} else {
printf("Invalid input. Please enter 1 or 0.\n");
}
return 0;
}
