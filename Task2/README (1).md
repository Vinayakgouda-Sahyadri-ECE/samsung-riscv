# -riscv-task-2

<!DOCTYPE html>
<html>
  <body>
<p>Task 2:compile C program using <b>RISC-V GCC/SPIKE</b> and also generate and collect the <b>RISC-V</b> object dump for both <b>-O1</b> and <b>-Ofast</b></p><br>
<ul><b>step-1:</b>
<li>once again repeat the task 1</li>
  <b>step-2:</b>
  <li>We must get the same output for both gcc and spike.</li>
  <img src="https://github.com/Vinayakgouda-Sahyadri-ECE/-riscv-task-2/blob/main/Screenshot%20from%202025-01-09%2021-54-14.png" alt="image-1" width="auto" height="auto">
  <b>step-3:</b>
  <li>Type spike -d pk ____.o for debugging</li>
  <b>step-4:</b>
  <li> use command <b> unti pc 0 100__ </b>and then add <b>reg 0 __ </b></li>
  <li> __ is filled by checking the -O1 and -Ofast(Ex:100b0,1000b4,reg 0 a2,reg 0 a0)</li>
  <img src="https://github.com/Vinayakgouda-Sahyadri-ECE/-riscv-task-2/blob/main/Screenshot%20from%202025-01-09%2022-26-23.png" alt="image-1" width="auto" height="auto"
  <b>step-5:</b>
  <li>we can verify the ouput by quitting and starting the <b>until pc 0 100__ </b>from wher we quit.</li>
  <img src="https://github.com/Vinayakgouda-Sahyadri-ECE/-riscv-task-2/blob/main/Screenshot%20from%202025-01-09%2022-04-13.png" alt="image-1" width="auto" height="auto"
  <b>step-6:</b>
  <li>Continue the same process till the end.</li>
  
  
  
</ul>
    
</body>
</html>
