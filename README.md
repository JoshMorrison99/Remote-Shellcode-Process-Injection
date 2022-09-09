## Remote Shellcode Process Injection

**Description**<br />
The process of injecting shellcode into a remote process starts by opening the process you want to inject the shellcode into (example: notepad.exe). The next step is to allocate memory in that remote process, we want to allocate enough memory to inject the size of our shellcode. The next step is to copy our shell code into the remote process, and finally, we want to create a thread on the remote process to execute our shellcode.
