# Round_Robin_Scheduling
Round Robin(RR) scheduling algorithm is mainly designed for time-sharing systems. 
This algorithm is similar to FCFS scheduling, but in Round Robin(RR) scheduling, preemption is added which enables the system to switch between processes.

Round Robin(RR) scheduling algorithm is mainly designed for time-sharing systems. 
This algorithm is similar to FCFS scheduling, but in Round Robin(RR) scheduling, preemption is added which enables the system to switch between processes.

  1.A fixed time is allotted to each process, called a quantum, for execution.

  2.Once a process is executed for the given time period that process is preempted and another process executes for the given time period.

  3.Context switching is used to save states of preempted processes.

  4.This algorithm is simple and easy to implement and the most important is thing is this algorithm is starvation-free as all processes get a fair share of CPU.

  5.It is important to note here that the length of time quantum is generally from 10 to 100 milliseconds in length.

Some important characteristics of the Round Robin(RR) Algorithm are as follows:

  1.Round Robin Scheduling algorithm resides under the category of Preemptive Algorithms.

  2.This algorithm is one of the oldest, easiest, and fairest algorithm.

  3.This Algorithm is a real-time algorithm because it responds to the event within a specific time limit.

  4.In this algorithm, the time slice should be the minimum that is assigned to a specific task that needs to be processed. Though it may vary for different operating systems.

  5.This is a hybrid model and is clock-driven in nature.

  6.This is a widely used scheduling method in the traditional operating system.

Important terms
  Completion Time It is the time at which any process completes its execution.

Turn Around Time This mainly indicates the time Difference between completion time and arrival time.
The Formula to calculate the same is: Turn Around Time = Completion Time – Arrival Time

Waiting Time(W.T): It Indicates the time Difference between turn around time and burst time.
And is calculated as Waiting Time = Turn Around Time – Burst Time
