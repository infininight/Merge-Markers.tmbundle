# TextMate Bundle for highlighting merge conflict markers

This bundle defines a simple injection grammar to highlight merge conflict markers across all filetypes.

## Installation

```
cd ~/Library/Application\\ Support/Avian/Bundles
git clone https://github.com/noniq/Merge-Markers.tmbundle
```

## Customization

Lines containing a merge marker will get the scope `comment.merge-marker` applied, so they will be styled like comments out of the box. To customize their appearance just edit your theme to include specific highlighting settings for `comment.merge-marker` or the following, even more specific scopes:

* `<<<<<<<` → `comment.merge-marker.yours`
* `|||||||` → `comment.merge-marker.original`
* `=======` → `comment.merge-marker.theirs`
* `>>>>>>>` → `comment.merge-marker.end`

