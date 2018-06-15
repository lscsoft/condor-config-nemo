This repository includes the HTCondor configuration in use at the UWM NEMO
computing cluster. There are 3 types of machines that run HTCondor.

1. The "submit" node where users run `condor_submit` and `condor_q`
2. The "execute" nodes where jobs match and execute
3. The "manager" node which negotiations job matching from the submit
node to the execute nodes
