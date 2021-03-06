# DEVs Git CTF
## Introduction

Welcome to the DEVs git Capture the Flag (CTF) competition!

If you can read this, then you've probably already done most of the setup, but please read the next section to make sure.

### Setting Up

#### Git

To make sure that Git is installed, run the following command in your terminal:

```sh
git --version
```

You should get back something like `git version 2.32.0`.

If you cannot run this command, please [install git on your machine](https://git-scm.com/downloads).

If you don't want to bother running the installation, consider using an online tool like [repl.it](https://replit.com) to setup a `bash` environment, or clone the repository from GitHub.

#### GitHub

Make sure that you have signed up for a [GitHub](https://github.com) account. This is required for the CTF (and probably for your degree at some point).


#### Challenge 9 Setup

For Challenge 9, you'll need to be a collaborator on the GitHub repo. In order to get this, do the following:

1. Send an email to `devs.ctf@gmail.com` from the email tied to your GitHub, and include your GitHub username in that email.
2. Accept the invitation email that GitHub sends you.

You'll also need the ability to link your machine to your GitHub account. The easiest way to do this is:

1. Clone the repository **using HTTPS**: `git clone https://github.com/<username>/<repo_name>.git`
2. When pushing code, it will prompt you for your GitHub username and password.

Note that if you've setup two factor authentication, you'll probably have to clone using SSH and then setup your SSH keys. See [here](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) for a step-by step guide for how to do this.

### Challenge Website

The CTF challenge will be run online at [this website](http://devs-ctf.australiaeast.azurecontainer.io:8000).

The CTF will only start after the presentation, so the questions won't be live until then.

### Getting Help

There will be DEVs exec team members walking around, who can help with any questions that you may have.

Additionally, there are the resources from the slides, and anything you can find on Google.

You are welcome to work in teams, but then you'll have to figure out how to split the prize.

### Hints

Some CTF challenges will offer hints for how to complete them. These hints will often come at a cost (points), but sometimes they are free, so it is worth checking.

A hint costs half the amount of points that completing the challenge would give you. e.g. an "Easy" challenge gives you 2 points, and it's hints will cost you 1 point.

## Flags

### What is a Flag?

A flag is simply a random string of 16 uppercase characters, e.g. `JWGDXBBHNSGDKMBL` (this isn't a valid flag, unfortunately).

The flags are hidden around this git repository, and the challenges describe how to earn these flags.

### Capturing Flags

Flags must be captured in order to earn points. The flags are captured by copy-and-pasting them into the appropriate field on the CTF website. Each challenge has a unique flag, so you'll have to complete each challenge in order to get the flags.

## Prizes

### Scoring

Capturing flags will grant you points, which give you a standing on the leaderboard.

The different challenges have different difficulty levels, which correspond to different amounts of points

* The 6 "Easy" challenges are worth 2 points each
* The 5 "Medium" challenges are worth 4 points each
* The 3 "Hard" challenges are worth 8 points each

### Available Prizes

1st  place: Google Home Mini

2nd place: DEVS Hoodie

3rd place: DEVS T-Shirt

## Challenges

### Types of Challenges

### What a Challenge Consists Of

Challenges consist of 1 or more files:

1. A `README.md` file that describes the challenge
2. A flag, matching the pattern described above
3. Additional files that are part of the challenge

Each challenge is on its own git branch, where challenge number `x` will be on branch `challenge/x`

### Challenge 0

#### Description

The very first challenge! If you can read this file, you can complete the challenge already. 

Simply copy the flag below and put it into the CTF platform to get your first point!

#### Flag

    YXEZPSELMPYQJKWJ

### Challenge 1


The first real challenge: checkout the `challenge/1` branch and view the `README.md` file.
