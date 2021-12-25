# ✨ Automate macOS Config with a BrewFile ✨
Easily install software and applications you use on your macOS by automating the process with [Homebrew](https://brew.sh) and a brewfile.

A brewfile is a text file that lists the commands Homebrew needs to install specific software and applications. 


### Step 1:
Create your brewfile

Be sure to include this command in your brewfile:

```$ brew tap Homebrew/bundle``` 

You can see mine here for inspiration: [my brewfile](https://github.com/LadyKerr/BrewFile/blob/main/brewfile.sh)

### Step 2:
Install [Homebrew](https://brew.sh) by pasting this command in your terminal:

```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Step 3:
Run `$ brew bundle` in your terminal and watch the magic happen.

If everything runs without error, you're in business and ready to use your apps 💃🏽
