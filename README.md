# Operating-Systems-CA
This is the solution sumbission for the Academic Task: Simulation Based Assignment of Operating System CSE316 for the Academic Year 2019.
# About Me

Name - Aman Srivastava

Registration No - 11715962

Section - K17SM

Roll No - B36

Group - B

# Problem 1
Considering the arrival time and burst time requirement of the process the scheduler schedules the processes by interrupting the processor after every 6 units of time and does consider the completion of the process in this iteration. The scheduler than checks for the number of process waiting for the processor and allots the processor to the process but interrupting the processor every 10 unit of time and considers the completion of the processes in this iteration. The scheduler checks the number of processes waiting in the queue for the processor after the second iteration and gives the processor to the process which needs more time to complete than the other processes to go in the terminated state.
The inputs for the number of requirements, arrival time and burst time should be provided by the user.
Consider the following units for reference.
Process    Arrival time    Burst time
P1   		 0    		20
P2   		 5    		36
P3    		13    		19
P4    		26    		42
Develop a scheduler which submits the processes to the processor in the defined scenario, and compute the scheduler performance by providing the waiting time for process, turnaround time for process and average waiting time and turnaround time.
# Problem 2
Write a program for multilevel queue scheduling algorithm. There must be three queues generated. There must be specific range of priority associated with every queue. Now prompt the user to enter number of processes along with their priority and burst time. Each process must occupy the respective queue with specific priority range according to its priority. Apply Round robin algorithm with quantum time 4 on queue with highest priority range. Apply priority scheduling algorithm on the queue with medium range of priority and First come first serve algorithm on the queue with lowest range of priority. Each and every queue should get a quantum time of 10 seconds. Cpu will keep on shifting between queues after every 10 seconds  i.e. to apply round robin algorithm OF 10 seconds on over all structure.
Calculate Waiting time and turnaround time for every process. The input for number of processes  should be given by the user.
# Screenshots
Problem 1
![c1](https://user-images.githubusercontent.com/49406379/55884253-630d1f00-5bc5-11e9-8dcd-d417f5f09b1b.JPG)

Problem 2
![c1](https://user-images.githubusercontent.com/49406379/55885920-6ce45180-5bc8-11e9-8532-e55fe226cd14.JPG)


