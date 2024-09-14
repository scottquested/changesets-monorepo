# changesets-monorepo

A minimal monorepo using changesets for releases.

## Setup

Pull the repository and run `pnpm i` to install the dependencies.

## Usage

Create a new branch and make changes to the packages. When you are ready to release, run `pnpm changeset` to create a new changeset. Commit the changeset and push the branch.

Once the branch is pushed, create a pull request and merge it. This will create a new release branch. When you're happy with the changeset PR, merge it.

This will trigger the GitHub Actions workflow to create a new tag and release. This will also trigger the fake Deploy step.
