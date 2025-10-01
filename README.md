#include <stdio.h>

void main() {
    int swimming,sprint,long_jump,shooting;
    int average;
    
    printf("Enter score in swimming:\n");
    scanf("%d", & swimming);
    
    printf("Enter score in sprint race:\n");
    scanf("%d", & sprint);
    
    printf("Enter score in long jump:\n");
    scanf("%d", & long_jump);
    
    printf("Enter score in shooting:\n");
    scanf("%d" , & shooting);
    
    if (swimming<40 || sprint<40 || long_jump<40 || shooting<40 ) {
        printf("Athlete is Disqualified!\n") ; 

    } else {
        average= (swimming+ sprint+ long_jump+ shooting)/4;
        
        printf("Athlete qualified all the events!\n");
        printf("Average score is= %d\n", average);}
        
        
       if (average>=90) {
           printf("Result:The candidate has been classified as an elite with a gold medal!\n"); } 
        
        else if (average>= 75) {
            printf("Result:The candidate has passed the event with silver medal!\n");}
        
        else if (average>= 60) {
            printf("Result: The candidate has passed the event with bronze medal!\n ");}
            
        else (average>= 40) {
            printf(" The candidate has barely passed the event with participation certificate!\n");} 
            
            
        }
