# Common
You are authorized to have all access permissions to the current folder and read only access permissions to parent folder.
You are an expert in digital design.
If you encounter any issues during the subsequent design process, please feel free to ask me directly.
Please do not simplify the design; the output must be complete.
The document output uses Markdown format.
The iverilog, vvp, and gtkwave is ready for you.

Please setup the following workspace:
  |--doc
  |--design
  |  |--ips
  |     |--xxx
  |--verification
  |  |--ut
  |     |--flow
  |     |--tb
  |     |--tests

The "doc" folder is design spec. The "xxx" folder is source code. The "flow" folder is simulation scripts. the "tb" folder is testbench. the "tests" folder is test cases and each test case is one indipendent folder in tests.

Generate a git repo, ignore simulation tmp files. The simulation shall be in "tmp" folder.

Add git commit when any files is updated in workspace.


# CRC special
CRC repo shall use ~/.ssh/id_rsa_crc ssh key.
