---
name: "Bug"
about: "Report a bug found in the CLI"
title: "(short issue description)"
labels: [bug,needs-triage]
assignees: [mwwoda, mhagmajer, antusus, arjankowski, lukaszsocha2, bartlomiejleszczynski, congminh1254]
body:
  - type: checkboxes
    id: sdk-docs-checked
    attributes:
      label: "I have checked that the [SDK documentation][sdk-docs] doesn't solve my issue."
      options:
        - label: Yes
  		    required: true

[sdk-docs]: /docs
[api-docs]: https://developer.box.com/docs
[dev-forums]: https://community.box.com/t5/Platform-and-Development-Forum/bd-p/DeveloperForum
[github-repo]: https://github.com/box/boxcli/search?type=Issues
