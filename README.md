# tox-win-manifest

This repository contains google `repo` manifest files for the
tox and uTox .

To use, install the google `repo` tool from https://github.com/jingyu/git-repo

    curl https://raw.githubusercontent.com/jingyu/git-repo/stable/repo > /usr/local/bin/repo
    chmod a+x /usr/local/bin/repo

Then run the following commands:

    mkdir tox
    cd tox
    repo init -u https://github.com/jingyu/tox-win-manifest.git
    repo sync

