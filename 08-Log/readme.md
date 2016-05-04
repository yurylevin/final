# Reviewing the repository history
> git log --oneline
> git log --oneline my_apple_app
> git log --oneline MyWindowsApp/code.txt
> git log --oneline MyWindowsApp
> git mv MyWindowsApp/code.txt MyWindowsApp/dll.txt
> git commit -m "moved code into dll"
See the history:
> git log --follow --oneline MyWindowsApp/dll.txt
> git log --follow --oneline -- MyConsoleApp/console.txt
> git log --follow --name-status --oneline MyWindowsApp/dll.txt
> git log --follow -p MyWindowsApp/dll.txt
diff --git a/MyWindowsApp/code.txt b/MyWindowsApp/dll.txt
diff --git a/MyWindowsApp/code.txt b/MyWindowsApp/code.txt
diff --git a/MyWindowsApp/code.txt b/MyWindowsApp/code.txt