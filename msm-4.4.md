# msm-4.4

* kernel.lnx.4.4.r44-rel
   * This branch was created from scratch and thus you can't use android-linux-stable as a base
   * Some upstream commits were dropped due to CAF changes, however all bug fixes are kept in one way or another
   * Some CAF changes were reverted to take upstream fixes (seemed better for me)
   * I've ported upstream commits where needed; as of my investigation, this branch has more upstream fixes that were left previously in android-linux-stable and I strongly recommend using this one
   * Upstream commits were ported if needed; in android-linux-stable some important fixes were dropped due to conflicts
   * Android-related changes from kernel_common were cherry-picked on the top of the tree
