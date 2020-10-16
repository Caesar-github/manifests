# Rockchip Debian/Buildroot SDK

The Default:

To initialize Linux source tree

$ repo init --repo-url=https://github.com/Caesar-github/repo --no-clone-bundle -u https://github.com/Caesar-github/manifests

To synchronize the source code

$ repo sync --no-clone-bundle

--

The Rockchip chips

Sync to the lastest release code:

$ repo init --repo-url=https://github.com/Caesar-github/repo --no-clone-bundle -u https://github.com/Caesar-github/manifests -b master -m rockchip_linux.xml

$ repo sync --no-clone-bundle

--
