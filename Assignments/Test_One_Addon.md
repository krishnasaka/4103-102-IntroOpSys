## Krishna Saka 
## Assignment2

#Test1 Helper

## 1.what is multi tasking?
A.The ability to execute more than one task at  the same time,a task being a program.
  in this,only one cpu is involved,but it switches from one task to another so quickly
  that it gives the appearence of executing al of the programs at the same time.

###Example:
            A user may wish to employ a word processor, a drawing program, 
            and a spreadsheet application simultaneously to produce a document.
            Without multitasking, The user need to do one by one where first he needs to open drawing proram later 
            opens the file and need to save like that one by one he needs to do.

##2.what is multiprogramming?
A.Multiprogramming is nothing but a rudimentary form of parallel processing in which several
 programs are run at the same time on a uniprocessor. since only one processor, there can be
 no true simultaneous execution of different programs.
              (or)
 A process is a program in execution. A process is controlled and scheduled by the
 operating system.
###Example:
        Consider a computer with 250 Mbytes of available memory (not used by the OS),a disk, a terminal,and a printer.
        Three programs,JOB1,JOB2,and JOB3,are submitted for execution at the same time 
        We assume minimal processor requirements for JOB2 and JOB3 and continuous disk and printer use by JOB3. 
        For a simple batch environment, these jobs will be executed in sequence.Thus,JOB1 completes in 5 minutes.
        JOB2 must wait until the 5 minutes are over and then completes 15 minutes after that. 
        JOB3 begins after 20 minutes and completes at 30 minutes from the time it was initially submitted.
        It is evident that there is gross underutilization for all resources when averaged over the required 30-minute time period.


## 3. what is multiprocessing?
A. multiprocessing is nothing but the use of two or more CPUs within a single computer system.
   It also refers to the ability of a system to support more than one processor and/or the ability 
   to allocate tasks between them.

### Example: 
           Linux,Unix. where these support multiprocessing concept.


## 4. What is multi thereaded?
A. Multithreading is a technique in which a process, executing an application, is
   divided into threads that can run concurrently.
### Example:
            An example is a database server that listens for and processes numerous client requests.
            With multiple threads running within the same process,switching back and forth among threads involves 
            less processor overhead than a major process switch between different processes.   

## 1. What is an instruction trace?
A. An instruction trace for a program is the sequence of instructions that execute for
   that process.
   
## 2. What are the common events that lead to the creation of process?
A. The common events that lead to the creation of a process are New batch job,interactive logon,
   created by OS to provide a service,spawned by existing process.


## 3. What does it mean to preempt a process?  
A. Process preemption occurs when an executing process is interrupted by the
   processor so that another process can be executed.  
  
 
## 4. What is swapping and what is its purpose?
A. Swapping is nothing but, moving part or all of a process from main memory to disk.
   When none of the processes in main memory is in the Ready state, the operating
   system swaps one of the blocked processes out onto disk into a suspend queue, so
   that another process may be brought into main memory to execute.

## 5. Why does Figure 3.9b have two blocked states?
A. There are two independent concepts: whether a process is waiting on an event
   (blocked or not), and whether a process has been swapped out of main memory
   (suspended or not). To accommodate this 2 × 2 combination, we need two Ready
   states and two Blocked states.

## 6. List four characteristics of a suspended process.
A. The four characterstics of a suspended process are:
   1. The process is not immediately available for execution. 
   2. The process may or may not be waiting on an event. If it is, this blocked condition is independent of the
      suspend condition, and occurrence of the blocking event does not enable the
      process to be executed. 
   3. The process was placed in a suspended state by an agent;
      either itself, a parent process, or the operating system, for the purpose of
      preventing its execution. 
   4. The process may not be removed from this state until
      the agent explicitly orders the removal.

## 7. List three general categories of information in a process control block.
A. The three general categories of information in a process are:
   Process identification, processor state information, and process control information. 

## 8. Why are two modes (user and kernel) needed?
A. The two modes of user and kernel are needed because,
   user mode has restrictions on the instructions that can be executed and the
   memory areas that can be accessed. This is to protect the operating system from
   damage or alteration. 
   In kernel mode, the operating system does not have these
   restrictions, so that it can perform its tasks.

## 9. What is the difference between an interrupt and a trap?
A. The difference between interrupt and trap is
   An interrupt is due to some sort of event that is external to and independent of the
   currently running process, such as the completion of an I/O operation. A trap
   relates to an error or exception condition generated within the currently running
   process, such as an illegal file access attempt.

## 10. Give three examples of an interrupt.
A.  The three examples of an interrupt are:
    Clock interrupt, I/O interrupt, memory fault.

## 11. What is the difference between a mode switch and a process switch?
A.  The differnce between a mode switch and a process switch is.
    A mode switch may occur without changing the state of the process that is
    currently in the Running state. A process switch involves taking the currently
    executing process out of the Running state in favor of another process. The process
    switch involves saving more state information.
    
    
 [Here is my reference link used for homework](http://www.nastooh.com/teaching/William_Stallings_Operating_Systems_7th_Edition.pdf)
