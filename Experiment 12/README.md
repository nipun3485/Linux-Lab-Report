# Experiment 12 – Building a Rule-Based Expert System and Process Management

## Part 1 – Medical Expert System Using Shell Script

### Objective
To design a rule-based medical expert system that takes symptoms as input and provides appropriate recommendations using conditional statements in shell scripting.

### Description
The script accepts multiple symptoms (comma separated), converts them to lowercase for case-insensitive matching, checks each symptom using conditional rules, and displays relevant recommendations. It also counts the total number of matched symptoms and provides a summary.

### Script Name
medical_expert.sh

### How to Run
1. Make the script executable:
   chmod +x medical_expert.sh

2. Run the script:
   ./medical_expert.sh

### Example Input
fever, cough, headache

### Output Screenshot
Add your screenshot here.

### Conclusion
Implemented a simple rule-based expert system using conditional checks and string processing in shell scripting.


---

## Part 2 – Process and Session Management Using Tmux

### Objective
To learn and demonstrate process/session handling using the `tmux` terminal multiplexer tool.

### Description
This part covers the installation, creation, detaching, listing, and attaching of tmux sessions. Tmux allows multiple terminal sessions to run in the background and helps manage long-running tasks efficiently.

### Installation

#### On Ubuntu/Debian
sudo apt update  
sudo apt install tmux

#### On CentOS/RHEL
sudo yum install tmux

#### On macOS
brew install tmux

### Basic Usage

#### Starting tmux
tmux

#### Creating a named session
tmux new-session -s session_name

#### Detaching from a session
Keyboard shortcut:  
Ctrl + b, then press d

#### Listing all sessions
tmux list-sessions

#### Attaching to a session
tmux attach-session -t session_name

### Essential Commands Summary
- Start a tmux session  
- Create a new named session  
- Detach from current session  
- List active sessions  
- Re-attach to an existing session  

### Screenshot
Add your tmux command screenshot here.

### Conclusion
This part demonstrated basic `tmux` operations, enabling efficient multitasking and background process management in Linux.
