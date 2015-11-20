---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
starred: false
keywords: []
description: ''
datePublished: '2015-11-20T21:32:27.998Z'
dateModified: '2015-11-20T21:31:52.181Z'
title: 'Major improvements to the Grid Beta Post Editor are afoot!'
author: []
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
sourcePath: _posts/2015-11-20-major-improvements-to-the-grid-beta-post-editor-are-afoot.md
published: true
url: major-improvements-to-the-grid-beta-post-editor-are-afoot/index.html
_type: Article

---
# Major improvements to the Grid Beta Post Editor are afoot!

Dear Grid early beta testers,
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/18a61dfb-6e9c-489e-ad80-bcfd3fa4cc86.png)

I'm the coder responsible for the former atrocity 🙈 known as the Grid Editor. After a couple of rewrites, teeth gnashing, disappearing content (& contenteditable expert), and [impressive][0] open-source [alternatives][1] emerging from the ether a little too late for us to use them...

If you have taken the time to try the Editor before this week, 🙇

Please give it another chance. I promise it's better.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/6c0bec49-2cff-49d8-997f-5e7da593787b.gif)

A few known issues as of Friday night in Leeds:

* cursor can jump (usually just a couple characters) if typing while post is saved and server version gets remerged while typing
* uploaded images don't automatically resize once measurements are done on the server
* list formatting can get messed up when copy/pasting list items
* image captions are set in a modal, behind a couple clicks (it would be nice if they were inline (you can of course just type captions under the image blocks))

Near-future todos:

* add a saving indicator
* warn if leaving page with unsaved changes
* make internal line breaks (shift+return) work (now they get cleaned out by server when reopened)
* un/applying blockquote formatting can cause explosions 💥 ... fix that
* replace (i) post meta modal with proper publish flow

[0]: http://prosemirror.net/
[1]: http://trix-editor.org/