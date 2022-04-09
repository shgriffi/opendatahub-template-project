# Release Process

The Open Data Hub Template Project is released on an as-needed basis. The process is as follows:

1. An issue is created proposing a new release with a changelog since the last release
1. All [OWNERS](OWNERS) must LGTM this release
1. An OWNER runs `git tag -s $VERSION` and inserts the changelog and pushes the tag with `git push $VERSION`
1. The release issue is closed
1. An announcement email is sent to `announcements@lists.opendatahub.io` with the subject `[ANNOUNCE] opendatahub-template-project $VERSION is released`