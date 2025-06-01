# Ex 2e Applications of Queue – FCFS
## DATE: 10/3/25
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
## Algorithm

1. Start with process, burst time, and waiting time arrays. 
2. Loop through each process from i = 0 to n-1. 
3. Compute tat[i] = burst_time[i] + wait_time[i]. 
4. End the algorithm.   

## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: Sanjana R
RegisterNumber:  212223240148
*/
 
int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[]) { 
   // calculating turnaround time by adding 
   // burst_time[i] + wait_time[i] 
   int i; 
   for ( i = 0; i < n ; i++) 
   tat[i] = burst_time[i] + wait_time[i]; 
   return 0; 
} 

```

## Output:

<img width="231" alt="image" src="https://github.com/user-attachments/assets/1c76f44f-fd12-4174-adee-58ee9eafb0ea" />



## Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
