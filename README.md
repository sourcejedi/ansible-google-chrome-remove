# sourcejedi.google_chrome_remove #

Remove the Google Chrome web browser.

This role does the reverse of `sourcejedi.google-chrome`.

However, it does not remove Google's package signing key.
Instructions on how to remove rpm keys are available here:
https://blog.laimbock.com/2014/05/02/how-to-remove-an-imported-gpg-key-from-rpm/comment-page-1/

## Status

This was only implemented for testing purposes.
I cannot really recommend using it.

Even if the role has already been applied, the following tasks may run and show as "changed": "Remove repo file" and "Re-install fedora-workstation-repositories if necessary".  This is expected.  They cancel each other out (though, they could have additional side effects).

## Requirements

This role is implemented for Fedora only.


## License

The role itself is licensed GPLv3, please open an issue if this creates any problem.
