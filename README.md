### sast
A tool for quickly saving your thoughts so when you come back you know exactly where you left off.

### Usage
<pre>
<b>$ sast save</b>
Finished:
  - implemented support for multiple users
  - regex bug fix
Unfinished:
  - database schema
Next:
  - implement cryptography from scratch
EOF(Ctrl-D)
</pre>


<pre>
<b>$ sast load</b>
Finished:
  - implemented support for multiple users
  - regex bug fix
Unfinished:
  - database schema
Next:
  - implement cryptography from scratch
</pre>

### How it works
When you `save` for the first time, a new dot file (.savestate) is created in the current directory. When you `load`, the last `save` is displayed.
