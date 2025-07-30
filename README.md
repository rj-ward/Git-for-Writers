# Using VS Code and Github for Writers

## Why use a text editor?

### You're not tied into any vendor.

Google has a bad habit of randomly locking author's work when it gets a sniff of something it doesn't like.

### Local first, backup anywhere

All of your files live on your device first and foremost. No internet? No problem.

### Version Control lets you edit without fear

Version control like Git stores a copy of your past work for you, with the changes you've made as you've gone along highlighted for comparison.

## 1. Set up your environment

### 1.1 Download the needed programs and files

- [Visual Studio Code download](https://vscodium.com/) This link leads to VC Codium, a tracker-free version of the VS Code editor released by Microsoft. It also doesn't have all that annoying AI built in. Win-win.
- [Git download](https://git-scm.com/downloads) This powers the version control back-end Git, which allows you to save edits with comments to GitHub for reference and backup.
- [Profile Import](https://github.com/rj-ward/Git-for-Writers/blob/main/Doc%20Writer.code-profile) (Hit the Download Raw File button on the top of the code block to save this to your computer) I tweaked this profile from the provided Doc Editing profile from Microsoft. It has a more typical sans-serif font vs a monotype font for the editing interface, along with some handy plugins recommended by microsoft.

### 1.2 Sign up for GitHub

You're probably reading this on GitHub right now. It's a website, you know what to do. Basic account things. 2FA is highly recommended both here and everywhere it's available.
[GitHub Account Setup - GitHub Docs](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account)

### 1.3 Install and set up git

1. Run the installer for Git for your OS. For Windows, it will install a program called Git Bash. This lets you use commands as if you're on Linux, which is the typical dev platform. Macs use similar on their backend, so they can use a Terminal.
2. Launch Git Bash for Windows or a Terminal on Mac or Linux.
3. Set your User Name for any commits by copying and pasting this command in the terminal, replacing the "John Doe" example for your name. If you don't want to use your real name, it can be anything you'd like. ```git config --global user.name "John Doe"```
4. Set the email you'd like to use to identify your commits by copying and pasting this command in the terminal, replacing the "John Doe" example for your name. ```git config --global user.email johndoe@example.com```

Congrats! With VS Code you won't have to touch the command line again!
