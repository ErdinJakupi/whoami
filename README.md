# Erdin Jakupi

The compare and pull request pages use different methods to calculate the diff for changed files:

Compare pages show the diff between the tip of the head ref and the current common ancestor (that is, the merge base) of the head and base ref.
Pull request pages show the diff between the tip of the head ref and the common ancestor of the head and base ref at the time when the pull request was created. Consequently, the merge base used for the comparison might be different.

