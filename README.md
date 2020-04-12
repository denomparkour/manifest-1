[![Download ATOM](https://sourceforge.net/sflogo.php?type=13&group_id=3199102)](https://sourceforge.net/p/atom-os-project/)
# ATOM #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/AtomOrganization/manifest -b ten

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
