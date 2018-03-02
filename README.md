# scrapbook-example
example for https://github.com/matsubara0507/scrapbook

## Usage

0. Rewrite `sites.yaml`
1. Setting GitHub Pages
2. Setting Travis CI
    - If use `.tavis.yml` in this repository, need env:
        - `GH_TOKEN` : GitHub personal token (only *public_repo*)
        - `GIT_NAME` : git config name
        - `GIT_EMAIL` : git config e-mail

If success TravisCI build, push `atom.xml` to this repository.

Access: https://matsubara0507.github.io/scrapbook-example/atom.xml
