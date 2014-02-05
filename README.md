Get Repo
---------------------------------------

    mkdir ~/bin
    PATH=~/bin:$PATH
    curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
    chmod a+x ~/bin/repo

Syncing DU Source
---------------------------------------

    mkdir ~/dud
    cd ~/dud
    repo init -u https://github.com/wantowan2/dud-android.git -b du44
    repo sync -f -j 4 | 8 | 16 | 24 | 32
