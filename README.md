# Btrfs module for ansible library

Create the home subvolume:

    - btrfs: name=home parent=/tmp/btrfs_root state=created
