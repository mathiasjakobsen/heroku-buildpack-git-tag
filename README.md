# heroku-buildpack-git-tag

Export the latest `git` tag (grabbed by `git describe --abbrev=0 --tags 2> /dev/null`), from the active branch, to the `GIT_TAG` environment variable for the application to access. This is useful if you are using Git tags to manage application versioning.

# Usage

Add the following to your apps `.buildpacks` file:

	https://github.com/mathiasjakobsen/heroku-buildpack-git-tag.git

# License

WTFPL
