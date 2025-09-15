Only use this rules when the PR is raised from rosetta branch
Get the localization keys from PR diff from default.it.json, default.de.json
Check those keys are available in default.en.json, it's not available then lflag those keys as not available in en file
Again check those key are available from their repective files in merging branch, for example check key is added in default.it.json(rosetta branch) is available in default.it.json file of merging branch(Eg: master, develop etc..).
if the key is available then check for key value if it's same then flag it has DUPLICATED
