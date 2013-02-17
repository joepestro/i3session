i3session
=========

i3session remembers what's running in your i3 workspaces by saving a session file (in ~/.i3/session). 
It is then able to restore the running processes (and simple orientation) to one or more workspaces.

Since i3session executes i3 commands sequentially (tree traversal), changing focus during restore will affect where clients open. The i3-nagbar will appear during restore with a message to remind you of this.

Saving a session
----------------

	% i3session save
	Saving...
	Session saved to ~/.i3/session


Restoring workspace 1
---------------------

	% i3session restore 1
	Restoring...
	Session restored from ~/.i3/session


Restoring all workspaces
------------------------

	% i3session restore
	Restoring...
	Session restored from ~/.i3/session
