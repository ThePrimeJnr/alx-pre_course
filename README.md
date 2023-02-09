![ALX](https://github.com/yiradesat/alx-pre_course/blob/master/images/alx-removebg-preview.png)
# My First Repository on GitHub - ALX Pre-School Project
Wow, I can't believe I'm starting my journey as a full-stack engineer and I get to use GitHub! I've heard a lot of great things about it and I'm so excited to dive in.
Here's what I need to do to get started:

## Step 1 - Create a GitHub Account
First things first, I need to create a GitHub account. If I don't already have one, I can create it for free at [GitHub.com](www.github.com/yiradesat). Having a GitHub account is crucial for all my projects at ALX School.

## Step 2 - Create a Personal Access Token
Next, I need to create a Personal Access Token on GitHub. This will allow me to access my repositories and authenticate myself. The tutorial on how to do this is available [here](https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token).

## Step 3 - Update My Profile on the Intranet
Once I have my GitHub username, I need to update my profile on the Intranet by adding my GitHub [username](www.github.com/yiradesat) here. This is important so the Checker can correct my work.

## Step 4 - Create My First Repository
Using the graphical interface on the GitHub website, I need to create my first repository. I'll name it `alx-pre_course` and give it a description of "I'm now an ALX student, this is my first repository as a full-stack engineer". I'll make it a public repository and don't need to add a README, .gitignore, or license.

## Step 5 - Open the Sandbox
On the intranet, I'll click the button to start the machine and then click the button to open a shell where I can start working.

## Step 6 - Clone My Repository
On the webterm of the sandbox, I'll run the following commands:

```bash
git clone https://{MY_PERSONAL_TOKEN}@github.com/{MY_USERNAME}/alx-pre_course.git
```
I'll replace {`MY_PERSONAL_TOKEN`} with my token from step 2 and {`MY_USERNAME`} with my username from step 1 and 2.

## Step 7 - Create the README.md and Push the Modifications
Next, I'll navigate to the `alx-pre_course` directory and create the file `README.md` with the content "My first readme". I'll then update my Git identity and add the new file to Git, commit the change with the message "My first commit", and push to the remote server/origin.

```bash
cd alx-pre_course/
echo 'My first readme' > README.md
git config --global user.email "myemail@example.com"
git config --global user.name "My Name"
git add .
git commit -m 'My first commit'
git push
```
And that's it! I've successfully pushed my first file in my first repository of the first task of my first ALX School project. I can now check my repository on GitHub to see if everything is good.
