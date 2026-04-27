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

<img width="975" height="369" alt="image" src="https://github.com/user-attachments/assets/235e1fd2-9356-4e0f-857b-5c28b6492e86" />

# step 4: frontend prompting
run;
<pre>
    Use react-sdk-patterns to build a payroll dashboard with wallet connection.
</pre>


<img width="975" height="466" alt="image" src="https://github.com/user-attachments/assets/61325793-7204-40c3-b9d2-1de25c68a7d6" />

# RESULT

<img width="1841" height="815" alt="Screenshot_27-4-2026_144429_localhost" src="https://github.com/user-attachments/assets/0df03303-ff7f-4f91-8e18-c29710952f7d" />

noTE;
you should also test the smart contracts
e.g Use rust-sdk-testing-patterns to create tests for salary distribution.

debugging: Check this contract for rust-sdk-pitfalls.

# good luck building
