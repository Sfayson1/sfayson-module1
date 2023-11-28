#Learn basic job control commands

## Pause a Running Process and Put It in the Background
In the image below we ran the command `top` I then ran the command `ctrl z` as you can see the terminal printed out that the process was stopped. 
<img width="949" alt="image" src="https://github.com/Sfayson1/sfayson-module1/assets/137829671/46ac17e7-a9b0-49a7-a40d-a2909bf6440b">

## List All Background Jobs
In the image below we ran the command `top`. This will list all jobs that you've started and suspended. 

<img width="500" alt="image" src="https://github.com/Sfayson1/sfayson-module1/assets/137829671/bc221e56-1585-4dce-b7fe-470d3aa9666c">

## Bring a Background Job to the Foreground
In the image below, I ran the command `fg %1` to bring the process to the foreground.

<img width="845" alt="image" src="https://github.com/Sfayson1/sfayson-module1/assets/137829671/46f1e8cc-2a2d-4c53-9395-7d4a90079038">

## Move a Foreground Job to the Background
In the image below, you see while the process was running we ran the command `ctrl z` to pause the process and we then ran the command `bg` to have the process run in the background. 

<img width="842" alt="image" src="https://github.com/Sfayson1/sfayson-module1/assets/137829671/b8dccbde-ba5a-4736-a7a5-4324ff6df51b">

## Terminate a Specific Job
In the image below, I use the `kill %2` command to terminate the job that I no longer want to run.

<img width="298" alt="image" src="https://github.com/Sfayson1/sfayson-module1/assets/137829671/a3761866-1444-423c-9346-37672af1495a">
