#include <stdio.h>
int main() {
    int emp_id[5], basic_salary[5], hra[5], da[5], gross_salary[5];
    int i;
    for (i = 0; i < 5; i++) {
        printf("Enter employee ID: ");
        scanf("%d", &emp_id[i]);

        printf("Enter basic salary for employee %d: ", emp_id[i]);
        scanf("%d", &basic_salary[i]);
    }
    for (i = 0; i < 5; i++) {
        hra[i] = 0.1 * basic_salary[i];
        da[i] = 0.05 * basic_salary[i];
        gross_salary[i] = basic_salary[i] + hra[i] + da[i];
    }
    printf("\nSalary Slip for Employees:\n");
    printf("----------------------------\n");
    for (i = 0; i < 5; i++) {
        printf("Employee ID: %d\n", emp_id[i]);
        printf("Basic Salary: %d\n", basic_salary[i]);
        printf("HRA: %d\n", hra[i]);
        printf("DA: %d\n", da[i]);
        printf("Gross Salary: %d\n", gross_salary[i]);
        printf("----------------------------\n");
    }

    return 0;
}
