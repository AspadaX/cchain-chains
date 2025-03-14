# cchain-chains
A remote storage that hosts publicly available automation configurations of cchain

# How to use this?
You may want to know about [`cchain`](https://github.com/AspadaX/cchain) if this is new to you. 

Then, you could use `ctrl + f` or `cmd + f` (on Macs) to search for whatever automation scripts you want here. 

Also, feel free to `git clone` this repo to your local directory, so that you can use the following command to bookmark them:
```bash
cchain add ./cchain-chains
```

# Indexes

## [Automatically fetch a repository](cchain_auto_fetch.json)
This chain allows you to pull and fetch the original repo all at once. 

## [Make a git automatically](cchain_auto_git.json)
It git commit and git push your changes automatically. It also uses LLMs to generate commit messages. On failure, it will use git reset to unset the commits. 

## [Make git automatically without using LLMs](cchain_auto_git_without_llm.json)
Auto git, but without LLMs. You will have to manually input a git commit message. 

## [Create a new branch in both local and remote](cchain_new_branch.json)
Then, it will open `zed` IDE for you. You may change that to `code` for opening VSCode instead. 

## [Setup an existing branch in a repo locally](cchain_resume_branch.json)
If you have a branch already in the remote repo, this chain will clone that repo with the specified branch, and it will open `zed` IDE for you. 

## [Use HF Mirror to download a model from within China](cchain_hf_download.json)
This chain allows you to download a model from HF Mirror, which works perfetcly in China. 
