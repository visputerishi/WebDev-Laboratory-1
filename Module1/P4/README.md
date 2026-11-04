# P4: GitHub README and Version Tags

## Aim
To document the project on GitHub and identify a release with a Git version tag.

## Work completed
- Added a root README with the laboratory overview, exercise links, and instructions to open the pages.
- Added a repository link and notes identifying sample portfolio placeholders.
- Prepared the first coursework milestone for a `v1.0.0` version tag.

## Commands
```sh
git tag -a v1.0.0 -m "Programming for Web Development I laboratory"
git show v1.0.0 --no-patch
git push origin main
git push origin v1.0.0
```

The tag and branch pushes publish changes to GitHub and should only be run when you are ready to publish.
