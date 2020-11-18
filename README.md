# How to add Codemagic merge checks?

**Prerequisites:**
* public repository or paid GitHub account
* repository added via UI, not with SSH or HTTPS URL

**Steps:**
* enable triggering pull_request creation and set it to match your branch pattern
* trigger one build by pull_request and confirm everything works
* navigate to repository "Settings" > "Branches" > "Add rule"
* fill in your branch name and check "Require status checks to pass before merging"
* check the Codemagic status check from the list and click "Create"
