## Git Setup: Windows

- Download and install [Visual Studio Code](https://code.visualstudio.com/) if you haven't done so.

- Download and install [Git for Windows](https://git-scm.com/download/win).

    - When you come across a window asking which default editor you would like `Git` to use, make sure to change from the selected default editor (Vim Editor - which is quite difficult to use, unless you already know your way around it, and you know how to exit it!) to *'Use Visual Studio Code as Git's default editor'*.

    - When you come across another window asking *'What would you like Git to name the initial branch after "git init"?'* choose *'Override the default branch name for new repositories'* and type *main* in the input box. This is because more and more developers are now moving away from naming the default repository branch as *master* and using the more inclusive term *main* instead.

    - For the rest of the options, leave them as is.

- **Git for Windows** includes a special Unix-based CLI called **Git Bash**; this is the recommended way to work with `Git` on Windows as the latter's **Command Prompt** is not compatible with `Git`.

- Another option is to use [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/en-us/windows/wsl/install).

- After finishing installation, open *Git Bash* and check the `Git` version:

```shell
$ git -v
git version x.xx.x.windows.1
```

- If you want to update `Git` via terminal:

```shell
$ git update-git-for-windows
```

<hr>

<table align="center">
   <tbody>
      <tr>
        <td>
            << Start: <a href="/README.md">README.md</a>
        </td>
        <td>
            < Previous: <a href="/assets/ch3.md">Git Installation: Requirements</a>
        </td>
        <td>
            Next: <a href="/assets/ch5.md">Git Setup: MacOS</a> >
        </td>
      </tr>
   </tbody>
</table>