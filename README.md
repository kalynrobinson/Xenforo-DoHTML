# [Shinka] DoHTML
Allows use of HTML in posts.

## Example
### Input
```HTML
[doHTML]<b>This text is bold</b>[/doHTML]
```

### Output
**This text is bold**

## Installation
* Copy the contents of `/upload` into the root of your Xenforo installation.
* From your control panel, go to the "install add-on" page. Upload `addon-shinka_dohtml.xml` and submit the form.

## Technical
* Strips out newlines-to-linebreaks so all line breaks must be explicitly declared with `<br/>`.
* Strips out `<script>...</script>` tags to prevent malicious JavaScript.