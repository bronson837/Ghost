# Ghost
Ghost is a Python-based script repair tool for Termux, PyCode, and ARMv7. It scans scripts for unsafe commands, root operations, and network manipulations, automatically comments out dangerous lines, creates backups, logs actions, and provides quick installation and recovery options for safe script management.


pkg update -y && pkg upgrade -y
pkg install -y git python
git clone git@github.com:bronson837/Ghost.git
cd Ghost
chmod +x ghost.py
python3 ghost.py
