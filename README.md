# pert-analyzer
Perform PERT Analysis on a set of tasks

PERT stands for "performance evaluation and review technique" and is designed to review a set of activities and identify the directed path that takes the longest time to complete. 

This program is designed to read a text file that lists: Vertex Name, a string of comma separated node predecessors, and the time required to complete the task.

SampleInput.txt
"V1" "" 5
"V2" "V1" 15
"V3" "V1,V2" 7
"V4" "V3,V1" 12

