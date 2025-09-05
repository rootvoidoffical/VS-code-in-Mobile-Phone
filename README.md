# VS-code-in-Mobile-Phone

#Intro
 In this post, we will see how you can install VS Code on an Android device. We will use one of the most popular Android terminal applications called Termux.
Visual Studio Code on mobile is a lightweight, browser-based adaptation that lets you write, edit, and manage code directly from your phone. When connected with GitHub, it allows you to clone repositories, push changes, create commits, and collaborate on projects without needing a laptop. It is best used for quick edits, reviewing pull requests, or managing code on the go.

NOW FOLLOW STEP BY STEP

##Step 1. Install Importent Package  In Termux.


 ```bash
 pkg update
 ```
```bash
 pkg upgrade
 ```
```bash
   pkg install proot-distro
```
```bash
    proot-distro list
```
```bash
  proot-distro install ubuntu
```

##Step 2. Login Ubuntu & Install Impoartent Peakge In Ubuntu.
Ubuntu is a free, open-source Linux operating system known for stability, security, and ease of use. It’s widely used for development, servers, and cloud computing.


```bash
  proot-disto login ubuntu
```
```bash
   apt update
```
```bash
 apt upgrade
```
```bash
 apt install wget
```
```bash
 wget https://github.com/coder/code-server/releases/download/v4.16.1/code-server-4.16.1-linux-arm64.tar.gz
```
```bash
  tar -xvf ./code-server-4.16.1-linux-arm64.tar.gz
```


##Step 3. Set password


```bash
cd code-server-4.16.1-linux-arm64
cd bin
```
```bash
       export PASSWORD="password"
```


##Step 4. Run Server


```bash
 ./code-server
```


##Final step. Open VS Code


 Open any browser ans run this command
 ```bash
localhoat:8080
```

