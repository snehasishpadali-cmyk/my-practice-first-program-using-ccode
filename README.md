##include <stdio.h>

int main() // <-- FIXED: Changed from 'void MAIN()' to 'int main()'
{
    int m1, m2, m3, m4, m5, total;
    float percentage;
    printf("Enter five marks: ");
    scanf("%d %d %d %d %d", &m1, &m2, &m3, &m4, &m5);
    m1 = 100;
    m2 = 100;
    m3 = 100;
    m4 = 100;
    m5 = 100;
    total = m1 + m2 + m3 + m4 + m5;
    percentage = (total / 500.0) * 100; // Good practice: use 500.0 for float calculation
    printf("Total marks: %.2d\n", total);
    printf("Percentage: %.2d%%\n", percentage);

    return 0; // <-- ADDED: Needed because main now returns an integer
}
 my-practice-first-program-using-ccode
this code use is weenter 5 subjet number and it gives us final total n umber and percentage
