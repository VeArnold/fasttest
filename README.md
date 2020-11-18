# How to add Codemagic merge checks?

Prerequisites:
* a) public repository or paid GitHub account
* b) repository added via UI, not with SSH or HTTPS URL

Steps:
* a) enable triggering pull_request creation and set it to match your branch pattern
* b) trigger one build by pull_request and confirm everything works
* c) navigate to repository "Settings" > "Branches" > "Add rule"
* d) fill in your branch name and check "Require status checks to pass before merging"
* e) check the Codemagic status check from the list and click "Create"
