# Leadfeeder Google Tag Manager (GTM) Template

Template for [Leadfeeder](https://www.leadfeeder.com) tag in
[Google Tag Manager](https://tagmanager.google.com)

## How to change the Leadfeeder GTM template

1. Modify the template code and add unit tests.
1. Import `template.tpl` into some existing GTM account where it could be tested
1. Make sure all unit tests run successfully.
1. Commit the changes
1. Create a PR and request a review.
1. After a PR has been approved, add the last commit's SHA with a description of the change to the `metadata.yaml` file.
1. Merge or ask the owner to merge your changes (do NOT use squash). The updated template will be automatically imported by the GTM using that last commit's SHA. For more details see https://developers.google.com/tag-manager/templates/gallery.
