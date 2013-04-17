Ext.ux.form.TinyMCETextArea

ExtJS form field - a text area with integrated TinyMCE WYSIWYG Editor.

Version: 2.5
Release date: 29.03.2013
ExtJS Version: 4.2.0
TinyMCE Version: 3.5.8
License: LGPL v2.1 or later, Sencha License

The integration is done by deriving from the Ext.form.field.TextArea.

Following issues are covered:

- Initialization in an initially visible and in an initially invisible tab.
- Correct place occupation by the initialization in any ExtJS layout.
- Correct resizing by the resizing of the underlying text area.
- Activation and deactivation of the WYSIWYG editor. Keeping of the cursor position by switching to the HTML text modus.
- Enabling and disabling of the WYSIWYG editor control.
- ReadOnly state support.
- Changing of WYSIWYG settings and CSS file for the editable contents on the fly.
- Pre-formatting of the HTML text in visible and invisible modus.
- Focusing of the WYSIWYG editor control.
- Marking invalid.
- Tracking dirty state.
- Skin "extjs" and the native ExtJS windows for the editor inline popups.
- Storing and restoring cursor position by inserting of a place holder over a popup window.
