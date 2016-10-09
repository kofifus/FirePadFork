# FirePadFork

- passes ESlint
- 'on' and 'off' return the firepad instance
- single file
- undo will combine edits with less than 500ms between them
- checkpoint frequency is 50 edits (instead of 100)
- delete revisions older than one week before the last checkpoint on document load
- save first checkpoint after CHECKPOINT_FREQUENCY edits since loading
- attribute changes (font/bold/etc) will not affect spaces around it
- removed ace support
- rich text copy/cut/paste
- update toolbar buttons state when attribute changes
- lineClassRemover only removes classes starting with 'firepad-'
- correctly handle attribute changes at the end of the line
- correctly handle cursor at the beginning of a non empty line
- correctly handle attributes when backspacing
- correctly pars spaces at the beginning of pasted html lines
- remove highlight key binding (so ctrl+h can be used for replace)

