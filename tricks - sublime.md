# Sublime tricks

<details>
<summary> Open file directly in sublime from CMD </summary>
    
<br/>
1. Open up notepad AS ADMINISTRATOR

2. Paste the following single line:
    @start "Sublime Text 3" "c:\YOUR\SUBLIME\INSTALL\sublime_text.exe" %*
    
    example : @start "Sublime Text 3" "C:\Program Files\Sublime Text 3\sublime_text.exe" %* 
    above is my sublime text  path
    
3. File -> Save As -> 
    %SystemRoot%\System32\sublime.cmd

#### Now to open a file in sublime text 3

```bash
sublime parser.py --add
```
<details>
