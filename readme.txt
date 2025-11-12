Simulated files by simplescalar to support the algorithm
Folders:
assembly : comtains assembly instructions before compilation for every bencmark.c file from benchmarks folder
benchmarks : c files hard-coded with different unroll factors
binaries : compiled benchmarks of the files from benchmarks
branch : txt files of branch simulations and behaviour file BHT after every access
branch_comps : modified bpred.c bpred.h sim-outrder.c files for printing branch log after simulations with out-order
cache : cache simulated files with sim out-order
obj : dis-assembled binaries 
profile : sim-profile simulated files
test : test files


Files:
analyser.cpp : source code to predict optimal factor from obj file // project 
Report fron simulations : report on analysed data from simulations to predict best factor that supports the algorithm
analyser : executable
analyser_readme.txt : commands to run analyser.cpp
uroll.txt : not unrolled benchmark disassembled obj file // input for analyser
result.txt: output file fro, analyser
readme.txt : this file 
Report.pdf:analyser approach and analysis
