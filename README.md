# Process Scheduling

Process scheduling is an important component of operating systems that deals with the problem of allocating CPU time to processes that are ready to run. The scheduling algorithm decides which process should be executed next, based on various factors such as priority, arrival time, and CPU burst time.

This program simulates three different process scheduling algorithms: First-Come-First-Served (FCFS), Shortest-Job-First (SJF), and Round-Robin (RR). The user can input a list of processes with their respective arrival time and CPU burst time, and the program outputs the order in which the processes are scheduled to run, as well as various statistics such as average waiting time and turnaround time.

## Usage

To use this program, simply clone this repository and compile the `main.c` file using a C compiler. For example, if you are using GCC on Linux or macOS, you can run the following command in the terminal:

```shell
gcc main.c -o scheduler
```

This will compile the program and create an executable file named `scheduler`. To run the program, simply execute this file in the terminal:

```shell
./scheduler
```

The program will prompt you to enter the number of processes, as well as the arrival time and CPU burst time for each process. Once you have entered all the necessary information, the program will output the order in which the processes are scheduled to run, as well as various statistics.

## Future Work

This program is a simple implementation of process scheduling algorithms and can be extended in several ways. Some possible future improvements include:

- Adding more scheduling algorithms, such as Priority Scheduling and Multi-Level Feedback Queue.
- Creating a graphical user interface to make it more user-friendly.

## Contributing

We welcome contributions to C Forge from the community. If you would like to contribute, please follow these steps:

1. Fork this repository
2. Create a new branch (`git checkout -b feature/my-feature`)
3. Make your changes and commit them (`git commit -am 'Add my feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a pull request

Please ensure that your code is well-documented and follows the [C Programming Style Guidelines](https://users.ece.cmu.edu/~eno/coding/CCodingStandard.html).
