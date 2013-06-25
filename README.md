# Yii git Hooks

git hooks to be used with Yii.

## What's Included?
### post-checkout

When switching branches:

- Gives a notice if new migrations are present, existing migrations are modified, or migrations have been removed
- Gives a notice if the seeds file has changed between branches

## Installation

To use, you can copy the hooks you want into your project's .git/hooks/ directory, or you can replace that directory with a symlink to a clone of this repository:

`cd ~/www/project-name/.git/; mv hooks hooks-old; ln -s ~/path/to/yii-git-hooks/repo/ hooks`
