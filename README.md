# cchain-chains
A remote storage that hosts publicly available automation configurations of cchain

# Indexes

## [Automatically fetch a repository](cchain_auto_fetch.json)
This chain allows you to pull and fetch the original repo all at once. 

## [Make a git automatically](cchain_auto_git.json)
It git commit and git push your changes automatically. It also uses LLMs to generate commit messages. On failure, it will use git reset to unset the commits. 

## [Make git automatically without using LLMs](cchain_auto_git_without_llm.json)
Auto git, but without LLMs. You will have to manually input a git commit message. 

## [Create a new branch in both local and remote](cchain_new_branch.json)
Then, it will open `zed` IDE for you. You may change that to `code` for opening VSCode instead. 
