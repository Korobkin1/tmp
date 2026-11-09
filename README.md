sed -i '/^[[:space:]]*tmpfs[[:space:]]\+\/tmp[[:space:]]/s/noexec,nosuid/defaults,noatime,nosuid,nodev/' /etc/fstab
