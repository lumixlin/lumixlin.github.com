Date: 2014-08-09
Title: Git note
Slug: git
Tags: note,linux

### View Code Change
- `git diff` = view changes between working directory and staging area (all files)
- `git diff --staged` = view changes between staging  area and remository (all files)
- `git diff version` = view changes between working and version (all files)
- `git diff version1 version2` = view changes between two version (all files)
- `git diff branch1 branch2` = view change between branch1 and branch2 (all files)
- `git diff file1` = view changes between working directory and staging area (only file1)

### Stage the changes
- `git add -p` = stage change in interactive mode, you can select which block to stage. when input with `s`, you can split the block into smaller.

### Remove, Move, Untrack files
- `git rm file` = remove file from index and staging area
- `git mv oldname newname` = mv file from old name to new name
- `git rm --cached file` = unstaged file. remove file from index but not in staging area

### Rollback
- `git reset --soft version` = set remository(HEAD) to version `version`, but keep working directory and staging area
- `git reset --mixed version` = set the remository and staging area to version `version`, but keep working directory
- `git reset --hard version` = set remository, staging area and working directory to version `version`
