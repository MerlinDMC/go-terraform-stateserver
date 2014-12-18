# golang terraform stateserver

An example HTTP backend for retrieving and storing terraform statefiles.

This example will store all statefiles in the filesystem starting at the given `-data_path`.

With a given `-data_path=/data/storage` the state url `http://<server>/folder/name-for-your-state` will be expanded to store the state in a file named `/data/storage/folder/name-for-your-state`.
