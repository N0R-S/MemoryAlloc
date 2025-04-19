## Usage: .\allocator <memory_size>

## allocator> RQ (ProcessID) <Process_SIZE> <Algorithm_Type>
### - Request Empty Block to a Process
<Algorithm_Type> : 
  W - Worst Fit ,
  F - First Fit ,
  B - Best Fit


## allocator> RL (Pid)
### - Release Allocated Process

## allocator> C 
### - Compaction 

## allocator> STAT
### - Display Free and Used Memory 

Example :
$ .\allocator 100000
$ RQ P0 20000 W

