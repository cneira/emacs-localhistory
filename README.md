# emacs-local-history
Add the local history feature like the one present in intellij, where the user could check the history of their changes on the file.
I have leveraged magit to stage and commit the changes on the current buffer to a local repository named ~/.localhistory-emacs, and added the symbol to after-save hook.

## Features

* After each save on the buffer, the file associated to the buffer is copied to a local git repo and changes commited.
* Navigate through commits  (TODO)

