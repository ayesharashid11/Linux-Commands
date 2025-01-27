
|-> 1. - file
|-> 2. l link
| -> 3. d directory
|   (read write execute)
l  rwx    rwx       rwx   
  (oowner)(permission)(other)   

  ->incbinary form:

  0 -> 000
  1 -> 001
  2 -> 010
  3 ->011
  4 -> 100
  5 -> 101
  6 ->110
  7 -> 111
  
For e.g:
  rw-rw-rw-  -> 011 | 001 | 110
