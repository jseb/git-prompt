# git-prompt
Adds some basic git status to the bash prompt, mimics the github display of
ahead/behind.

## Screenshots
Ahead and behind, yellow indicates uncomitted changes.

![Alt text](https://raw.github.com/jseb/git-prompt/screenshots/screenshots/1.png)

Ahead, red color = untracked files.

![Alt text](https://raw.github.com/jseb/git-prompt/screenshots/screenshots/2.png)

Up to date, with one stash. Green color means working directory clean.

![Alt text](https://raw.github.com/jseb/git-prompt/screenshots/screenshots/3.png)

## Try it out
By simply pasting this in your terminal:

```
source <(curl https://raw.github.com/jseb/git-prompt/master/git-prompt) \
	&& export PROMPT_COMMAND=git_prompt
```

## Installation
Clone the repo (or just download the file), and add this to the end of your
.bash_profile:

```
source path/to/git-prompt/git-prompt
export PROMPT_COMMAND=git_prompt
```
