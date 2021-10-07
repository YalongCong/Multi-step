# Multi-step
This package provides an implementation of the multi-step explicit solvent model of molecular dynamics (MD) simulation.

Requirements

   gcc (version >= 5.4.0) to compile file
   AMBER (suggent AMBER18) to generate the force field parameters files.

Install
(1). Extract the files in some location (we use /home/myname as an example here)
  cd /home/myname
  tar zxvf multi-step.tar.bz2

(2). Compile file 
  cd /home/myname/multi-step
  make
The /home/myname//multi-step/bin folder appears and contains the "md, md.OMP, and water_box" three files, indicating that the compilation is successful 

(3). Set environment variables 
  adding the line
  export PATH=$PATH:/home/myname//multi-step/bin
  to your startup file (e.g., ~/.bashrc)
