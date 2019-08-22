# heroku-buildpack-git-tag

Exports the latest `git` tag, from the repository, to the `GIT_TAG` environment variable, for the application to access. This is useful if you are using Git tags to manage application versioning.


# Prerequisites 

Environment varibales `GITHUB_REPO` and `GITHUB_TOKEN` must be set in the containers environment. The buildpack will fetch these at buildtime, and will fail if not present. 

# Usage

Add the following to your `.buildpacks` file:

	https://github.com/mathiasjakobsen/heroku-buildpack-git-tag.git

# License

WTFPL
