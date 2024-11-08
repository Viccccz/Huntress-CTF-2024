# Description

![image](https://github.com/user-attachments/assets/3f2f8122-d020-4cc4-99a3-b1c78921e714)

## Solution

1. Check the DNS record given.<br>
   `dig txt ctf.games`

> [!TIP]
> Can either use the command `dig <file>` or any online DNS Text record checkers.<br>
> [DNS Lookup Text Record](https://mxtoolbox.com/txtlookup.aspx)

2. We'll notice there are some weird numbers.<br>

   ![image](https://github.com/user-attachments/assets/9d434471-c952-4a05-af42-d3c52fe13246)

   ![image](https://github.com/user-attachments/assets/593eb85a-e232-44b0-9830-b1f1278d7292)

3. Convert it from octal.

> [!TIP]
> Online converter, [CyberChef](https://gchq.github.io/CyberChef/)

4. Get the flag.
