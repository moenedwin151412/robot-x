

# 2026-02-25 Round 1

## KIMI R1_0_kimi_report.md
0. 
common_rule.md

1. 
The simple description of CRC module is in ../robot-x/crc_feature.md.
Please generate a detail design specification document (markdown format) firstly in doc folder.
ask me if you have any question.

2. 
8 questions

3. 
how to generate DONE interupt

4. 
Add data length configuration and generate DONE interrutp.

5. 
it looks fine. please generate doc/kimi_report.md file to log all communication.

## GEMINI R1_1_gemini_report.md
0. 
common_rule.md

You are authorized to have all access permissions to the current folder and read only access permissions to parent folder.
You are an expert in digital design.
If you encounter any issues during the subsequent design process, please feel free to ask me directly.
Please do not simplify the design; the output must be complete.
The document output uses Markdown format.
The iverilog, vvp, and gtkwave is ready for you.

1. 
read doc/kimi_report.md and doc/crc_design_spec.md to underdand previous task.

2. 
generate RTL

3. 
generate a filelist file, and do not use `include in crc_top.v

4. 
Add git commit when any files is updated in workspace.

5. 
start creating the verification environment.

6. 
add several functional test cases in verification/ut/tests, and ensure that it easy to run different test cases.

7. 
RTL code must be complete, do not simplify the RTL code.

8. 
fixed_poly_sel_reg functionality missed

9. 
double check design spec and RTL, if any other missing.

10. 
fix warning using iverilog, do not start simulation

11. 
start simulation

12. 
please generate doc/gemini_r1_report.md file to log all communication.

=> GEMINI can not fix shell & Verilog TB error.


## KIMI R1_2_kimi_report.md

0. 
read doc/gemini_r1_report.md to underdand previous task.

1. 
delete all debug cases

2. 
push repo to remote repo: git@github.com:moenedwin151412/crc.git, and it is an empty repo.

3. 
double check design spec and RTL, if any other missing.

4. 
start simulation

=> KIMI fixed shell and TB error.

5. 
add tmp folder and all simulation files are in tmp folder. each test case is in individual folder.
add default simulation timeout time 1ms.

6. 
add test case for 100% function coverage.
add several test cases or 100% function coverage.





please generate doc/R1_2_kimi_report.md file to log all communication after read doc/gemini_r1_report.md. 


# 2026-02-25 Round 0

0. 
Please record all communication in crc_record.md file.

1. 
The simple description of CRC module is in ./crc_feature.md.
Please generate a detail design specification document (markdown format) firstly in doc folder.
ask me if you have any question.

2. 
generate .csv file for register map.
do not use memory to store data. calculate on the fly.
The AHB Lite slave supports byte/halfword/word access, and support burst 4/8/16 for raw data region.

3. 
according to design specification, generate crc RTL and testbench. ask me if you have any question.
