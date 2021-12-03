hello-world
===========

This is just a simple "Hello World" project meant to be used as a skeleton template for writing KWin scripts. The information on how to write these scripts, and how to set up your workflow is fragmented and hard to find. Expecially updated information. This way, I don't need to consult Google every time I want to write a quick sqript to solve a specific problem. :D

To use this repo, simply put your own code in [contents/code/main.js ](contents/code/main.js), modify [metadata.desktop](metadata.desktop) and run `make install` (or `make update`).

Tips
====
When developing KWin scripts, I usually replace kwin using `kwin --replace 2>&1 | grep "kwin_scripting"`. This lets me see `print()` statements from the scripts in the console.

To reload a script, simply use `make reload`. This effectively does the same thing as:
- System Settings 
  - go to Window Management 
    - go to Kwin-scripts 
      - Disable \<script> 
      - click Apply
      - Enable \<script> 
      - click Apply
  
  
Copyright
=========
This repo is released under [MIT](LICENSE.md) license. Copyright &copy; 2021 - Thomas Hellström.

