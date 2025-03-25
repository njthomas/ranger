Abandoning this patch.
======================

While this feature works, it has the unfortunate side effect that prevents the user from unselecting files within a narrowed context and run narrow again to show the new subset of narrowed files.

So instead we added a new command (`:narrow!`) in another branch and submitted a pull-request for that patch instead.

While this side-effect would not be the end of the world, users working in a narrowed context would probably want to stay inside it until they are done, so adding a new command is really the way to go.
