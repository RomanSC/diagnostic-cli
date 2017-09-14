# Command Line Interpreter diagnostic

## Questions

___Note___ Answer the following questions with the syntax appropriate to your operating system.

Situation: you are working on a computer with the following folder (directory) structure:
```
C:
 |--alpha
 |
 |--beta
    |--beta1

```

Your CLI window prompt is of the form:
```
C:\alpha >

```

Mine is like this:
```
[I] /home/roman 
roman: _
```

1. What is your operating system?
```
I use Arch Linux as my operating system. I install my operating system through the command line so I know how to use it.
```

2. What command(s) do you enter to show the files contained within `alpha`?
```
If alpha is a directory I would type:

l alpha/

Because I have aliased l to ls -a in my fish shell config.

```

3. What command(s) do you enter to move into the `beta` folder?
```
cd beta/
```

4. Now that you are in the `beta` folder, what command(s) do you enter to create a file named `betafile.txt`?
```
touch betafile.txt

or even better:
echo "Text in betafile" >> betafile.txt
```

5. What command(s) do you enter to add a new folder, `beta2`?
```
mkdir beta2/
```

6. What command(s) do you use to delete the folder `alpha`?
```
rm -r alpha/
```

I modified my fish and bash shell configs to remember the last folder I was in when new shell instances are created, to use vi keybindings, output to clipboard, and a few other things.
