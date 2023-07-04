# OMP_kronos
Templates for Oh My Posh

## Examples
###kronos.omp.json
This is the base file. The features from left to right are:-
<ul>
  <li>OS Flavour</li>
  <li>Running user</li>
  <li>Host name, truncated to remove any domain after the machine name such as <b>machine.example.com</b> to show as <b>machine</b>.</li>
  <li>Current working directory, optimised to shorten to two significant directories and directory delimiters.</li>
>  <li>The background of this field will change to a deeper red if the CWD is not writable.</li>
  <li>Command status, turns red on the failure of the previous command.</li>
</ul>

<img src="https://github.com/ArthurMitchell42/OMP_kronos/blob/main/images/basic.png" alt="Basic layout"> </a>

<ul>
  <li>If the CWD contains a git repository the git balloon will appear.</li>
  <li>The brach will be displayed.</li>
</ul>

<img src="https://github.com/ArthurMitchell42/OMP_kronos/blob/main/images/basic_git.png" alt="Basic layout"> </a>

<ul>
  <li>If there are modified files the colour of the background will change and the file count is displayed.</li>
</ul>

<img src="https://github.com/ArthurMitchell42/OMP_kronos/blob/main/images/basic_git_mod.png" alt="Basic layout"> </a>

<ul>
  <li>If there are modified files in staging the file count for them is displayed.</li>
</ul>

<img src="https://github.com/ArthurMitchell42/OMP_kronos/blob/main/images/basic_git_staged.png" alt="Basic layout"> </a>
