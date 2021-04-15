# android-linux-upstream
##### Android CAF Linux kernel source with Linux stable and Google's kernel_common trees merged in.
Source used to merge Linux stable: https://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git

Source used to merge kernel_common: https://github.com/aosp-mirror/kernel_common

Android-related kernel_common changes are selected using following command:
```
git log --oneline --since [LAST_STABLE_MERGE] | grep 'ANDROID|UPSTREAM|BACKPORT'
```
Then they are cherry-picked.
