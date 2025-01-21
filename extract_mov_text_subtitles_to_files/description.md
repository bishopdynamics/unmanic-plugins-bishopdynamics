Only mov_text/94213 subtitle streams found in the file will be exported as \*.srt files in the same directory as the original file.

:::warning
This plugin is not compatible with linking as the remote link will not have access to the original source file's directory.
:::

:::warning
This plugin does not remove the stream from the source file. To do that, use `remove_streams_by_codec` after this one.
:::

:::note
This Plugin does not contain a file tester to detect files that contain SRT subtitle streams.
Ensure it is pared with another Plugin.
:::
