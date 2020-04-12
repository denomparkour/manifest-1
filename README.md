[![Download ATOM](https://sourceforge.net/sflogo.php?type=16&group_id=3199102)](https://sourceforge.net/p/atom-os-project/)

[![TG chat](https://img.shields.io/badge/Support-Telegram-%23e52c5f.svg?style=for-the-badge&logo=telegram&&labelColor=121217)](https://t.me/atomosofficial)


# ATOM #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/AtomOrganization/manifest -b ten-aosp

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```

To apply for official builds click <a href="https://github.com/AtomOrganization/manifest/blob/ten/apply_for_official.md">HERE</a> for more info
