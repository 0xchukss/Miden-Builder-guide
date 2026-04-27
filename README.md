# Miden-Builder-guide

## requirements
- claude code, codex or cursor
- english language (hehe)

# step 1: install skills
run;
a. cursor
<pre>
    git clone https://github.com/0xMiden/agent-skills.git
  ln -sf "$(pwd)/agent-skills/skills" ~/.cursor/skills
</pre>

b. claude
<pre>
    git clone https://github.com/0xMiden/agent-skills.git
  ln -sf "$(pwd)/agent-skills/skills" ~/.claude/skills
</pre>

c. codex
<pre>
    git clone https://github.com/0xMiden/agent-skills.git
  ln -sf "$(pwd)/agent-skills/skills" ~/.codex/skills
</pre>

i used antigravity agent,


<img width="1915" height="962" alt="anti 1 skills" src="https://github.com/user-attachments/assets/e696b9f2-cebf-49b1-87be-5a5631a9a08d" />


# step 2; prompt to create project folder and initialize
run;
<pre>
    cargo new payroll-miden
  cd payroll-miden
</pre>

<img width="1447" height="950" alt="image" src="https://github.com/user-attachments/assets/1e54ac72-8d30-4c2d-94fc-7a65365dd1ed" />


# step 3; create a task
run,
<pre>
    Build a private payroll smart contract on Miden using Rust.
  Use accounts and notes.
  Employees should receive salary privately.
  Add unit tests.
</pre>

all these ARE SAMPLES. NOTE

<img width="975" height="466" alt="image" src="https://github.com/user-attachments/assets/61325793-7204-40c3-b9d2-1de25c68a7d6" />
