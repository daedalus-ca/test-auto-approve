# test-auto-approve

Test github pipeline to auto approve a flake bump.

## Install

* Follow this guide: https://docs.github.com/en/apps/creating-github-apps/registering-a-github-app/registering-a-github-app
* Create a GitHub app `auto-approve-app` in your GH organization
  * github.com/<org>/ -> Settings -> Developer Settings -> GitHub Apps -> New GitHub App
    * Add a name and Homepage URL
    * Add Repository Permissions
      * Actions: RO
      * Contents: RW
      * Metadata: RO
      * Pull Requests: RW
      * Workflows: RW

* Install this app into your organization
  * github.com/<org>/ -> Settings -> Developer Settings -> GitHub Apps -> Select `auto-approve-app` -> Install App
    * Only select repositories:
      * <test-repo>
* Find app_id
  * github.com/<org>/ -> Settings -> Developer Settings -> GitHub Apps -> Select `auto-approve-app`
  * you find the app_id in the `General` section

* FOO

