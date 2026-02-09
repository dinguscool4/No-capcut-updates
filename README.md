# no capcut updates
a lightweight python script to block capcut from automatically updating, ensuring you stay on your preferred version.

## features
automated blocking: prevents capcut's update executable from running.

persistent: maintains your version choice without manual intervention.

simple: single-file execution.

## usage
ensure you have python installed.

run the script with administrative privileges:

Bash
python main.py
## how it works
the script identifies the capcut update directory and modifies permissions or replaces the executable with a dummy file to break the update cycle.
