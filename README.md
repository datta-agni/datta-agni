<!doctype html>
<html>
<head>
<meta charset='UTF-8'><meta name='viewport' content='width=device-width initial-scale=1'>

<style type='text/css'>html {overflow-x: initial !important;}:root { --bg-color:#ffffff; --text-color:#333333; --select-text-bg-color:#B5D6FC; --select-text-font-color:auto; --monospace:"Lucida Console",Consolas,"Courier",monospace; --title-bar-height:20px; }
.mac-os-11 { --title-bar-height:28px; }
html { font-size: 14px; background-color: var(--bg-color); color: var(--text-color); font-family: "Helvetica Neue", Helvetica, Arial, sans-serif; -webkit-font-smoothing: antialiased; }
body { margin: 0px; padding: 0px; height: auto; inset: 0px; font-size: 1rem; line-height: 1.42857; overflow-x: hidden; background: inherit; tab-size: 4; }
iframe { margin: auto; }
a.url { word-break: break-all; }
a:active, a:hover { outline: 0px; }
.in-text-selection, ::selection { text-shadow: none; background: var(--select-text-bg-color); color: var(--select-text-font-color); }
#write { margin: 0px auto; height: auto; width: inherit; word-break: normal; overflow-wrap: break-word; position: relative; white-space: normal; overflow-x: visible; padding-top: 36px; }
#write.first-line-indent p { text-indent: 2em; }
#write.first-line-indent li p, #write.first-line-indent p * { text-indent: 0px; }
#write.first-line-indent li { margin-left: 2em; }
.for-image #write { padding-left: 8px; padding-right: 8px; }
body.typora-export { padding-left: 30px; padding-right: 30px; }
.typora-export .footnote-line, .typora-export li, .typora-export p { white-space: pre-wrap; }
.typora-export .task-list-item input { pointer-events: none; }
@media screen and (max-width: 500px) {
  body.typora-export { padding-left: 0px; padding-right: 0px; }
  #write { padding-left: 20px; padding-right: 20px; }
}
#write li > figure:last-child { margin-bottom: 0.5rem; }
#write ol, #write ul { position: relative; }
img { max-width: 100%; vertical-align: middle; image-orientation: from-image; }
button, input, select, textarea { color: inherit; font: inherit; }
input[type="checkbox"], input[type="radio"] { line-height: normal; padding: 0px; }
*, ::after, ::before { box-sizing: border-box; }
#write h1, #write h2, #write h3, #write h4, #write h5, #write h6, #write p, #write pre { width: inherit; }
#write h1, #write h2, #write h3, #write h4, #write h5, #write h6, #write p { position: relative; }
p { line-height: inherit; }
h1, h2, h3, h4, h5, h6 { break-after: avoid-page; break-inside: avoid; orphans: 4; }
p { orphans: 4; }
h1 { font-size: 2rem; }
h2 { font-size: 1.8rem; }
h3 { font-size: 1.6rem; }
h4 { font-size: 1.4rem; }
h5 { font-size: 1.2rem; }
h6 { font-size: 1rem; }
.md-math-block, .md-rawblock, h1, h2, h3, h4, h5, h6, p { margin-top: 1rem; margin-bottom: 1rem; }
.hidden { display: none; }
.md-blockmeta { color: rgb(204, 204, 204); font-weight: 700; font-style: italic; }
a { cursor: pointer; }
sup.md-footnote { padding: 2px 4px; background-color: rgba(238, 238, 238, 0.7); color: rgb(85, 85, 85); border-radius: 4px; cursor: pointer; }
sup.md-footnote a, sup.md-footnote a:hover { color: inherit; text-transform: inherit; text-decoration: inherit; }
#write input[type="checkbox"] { cursor: pointer; width: inherit; height: inherit; }
figure { overflow-x: auto; margin: 1.2em 0px; max-width: calc(100% + 16px); padding: 0px; }
figure > table { margin: 0px; }
thead, tr { break-inside: avoid; break-after: auto; }
thead { display: table-header-group; }
table { border-collapse: collapse; border-spacing: 0px; width: 100%; overflow: auto; break-inside: auto; text-align: left; }
table.md-table td { min-width: 32px; }
.CodeMirror-gutters { border-right: 0px; background-color: inherit; }
.CodeMirror-linenumber { user-select: none; }
.CodeMirror { text-align: left; }
.CodeMirror-placeholder { opacity: 0.3; }
.CodeMirror pre { padding: 0px 4px; }
.CodeMirror-lines { padding: 0px; }
div.hr:focus { cursor: none; }
#write pre { white-space: pre-wrap; }
#write.fences-no-line-wrapping pre { white-space: pre; }
#write pre.ty-contain-cm { white-space: normal; }
.CodeMirror-gutters { margin-right: 4px; }
.md-fences { font-size: 0.9rem; display: block; break-inside: avoid; text-align: left; overflow: visible; white-space: pre; background: inherit; position: relative !important; }
.md-fences-adv-panel { width: 100%; margin-top: 10px; text-align: center; padding-top: 0px; padding-bottom: 8px; overflow-x: auto; }
#write .md-fences.mock-cm { white-space: pre-wrap; }
.md-fences.md-fences-with-lineno { padding-left: 0px; }
#write.fences-no-line-wrapping .md-fences.mock-cm { white-space: pre; overflow-x: auto; }
.md-fences.mock-cm.md-fences-with-lineno { padding-left: 8px; }
.CodeMirror-line, twitterwidget { break-inside: avoid; }
svg { break-inside: avoid; }
.footnotes { opacity: 0.8; font-size: 0.9rem; margin-top: 1em; margin-bottom: 1em; }
.footnotes + .footnotes { margin-top: 0px; }
.md-reset { margin: 0px; padding: 0px; border: 0px; outline: 0px; vertical-align: top; background: 0px 0px; text-decoration: none; text-shadow: none; float: none; position: static; width: auto; height: auto; white-space: nowrap; cursor: inherit; -webkit-tap-highlight-color: transparent; line-height: normal; font-weight: 400; text-align: left; box-sizing: content-box; direction: ltr; }
li div { padding-top: 0px; }
blockquote { margin: 1rem 0px; }
li .mathjax-block, li p { margin: 0.5rem 0px; }
li blockquote { margin: 1rem 0px; }
li { margin: 0px; position: relative; }
blockquote > :last-child { margin-bottom: 0px; }
blockquote > :first-child, li > :first-child { margin-top: 0px; }
.footnotes-area { color: rgb(136, 136, 136); margin-top: 0.714rem; padding-bottom: 0.143rem; white-space: normal; }
#write .footnote-line { white-space: pre-wrap; }
@media print {
  body, html { border: 1px solid transparent; height: 99%; break-after: avoid; break-before: avoid; font-variant-ligatures: no-common-ligatures; }
  #write { margin-top: 0px; padding-top: 0px; border-color: transparent !important; padding-bottom: 0px !important; }
  .typora-export * { -webkit-print-color-adjust: exact; }
  .typora-export #write { break-after: avoid; }
  .typora-export #write::after { height: 0px; }
  .is-mac table { break-inside: avoid; }
  .typora-export-show-outline .typora-export-sidebar { display: none; }
}
.footnote-line { margin-top: 0.714em; font-size: 0.7em; }
a img, img a { cursor: pointer; }
pre.md-meta-block { font-size: 0.8rem; min-height: 0.8rem; white-space: pre-wrap; background: rgb(204, 204, 204); display: block; overflow-x: hidden; }
p > .md-image:only-child:not(.md-img-error) img, p > img:only-child { display: block; margin: auto; }
#write.first-line-indent p > .md-image:only-child:not(.md-img-error) img { left: -2em; position: relative; }
p > .md-image:only-child { display: inline-block; width: 100%; }
#write .MathJax_Display { margin: 0.8em 0px 0px; }
.md-math-block { width: 100%; }
.md-math-block:not(:empty)::after { display: none; }
.MathJax_ref { fill: currentcolor; }
[contenteditable="true"]:active, [contenteditable="true"]:focus, [contenteditable="false"]:active, [contenteditable="false"]:focus { outline: 0px; box-shadow: none; }
.md-task-list-item { position: relative; list-style-type: none; }
.task-list-item.md-task-list-item { padding-left: 0px; }
.md-task-list-item > input { position: absolute; top: 0px; left: 0px; margin-left: -1.2em; margin-top: calc(1em - 10px); border: none; }
.math { font-size: 1rem; }
.md-toc { min-height: 3.58rem; position: relative; font-size: 0.9rem; border-radius: 10px; }
.md-toc-content { position: relative; margin-left: 0px; }
.md-toc-content::after, .md-toc::after { display: none; }
.md-toc-item { display: block; color: rgb(65, 131, 196); }
.md-toc-item a { text-decoration: none; }
.md-toc-inner:hover { text-decoration: underline; }
.md-toc-inner { display: inline-block; cursor: pointer; }
.md-toc-h1 .md-toc-inner { margin-left: 0px; font-weight: 700; }
.md-toc-h2 .md-toc-inner { margin-left: 2em; }
.md-toc-h3 .md-toc-inner { margin-left: 4em; }
.md-toc-h4 .md-toc-inner { margin-left: 6em; }
.md-toc-h5 .md-toc-inner { margin-left: 8em; }
.md-toc-h6 .md-toc-inner { margin-left: 10em; }
@media screen and (max-width: 48em) {
  .md-toc-h3 .md-toc-inner { margin-left: 3.5em; }
  .md-toc-h4 .md-toc-inner { margin-left: 5em; }
  .md-toc-h5 .md-toc-inner { margin-left: 6.5em; }
  .md-toc-h6 .md-toc-inner { margin-left: 8em; }
}
a.md-toc-inner { font-size: inherit; font-style: inherit; font-weight: inherit; line-height: inherit; }
.footnote-line a:not(.reversefootnote) { color: inherit; }
.reversefootnote { font-family: ui-monospace, sans-serif; }
.md-attr { display: none; }
.md-fn-count::after { content: "."; }
code, pre, samp, tt { font-family: var(--monospace); }
kbd { margin: 0px 0.1em; padding: 0.1em 0.6em; font-size: 0.8em; color: rgb(36, 39, 41); background: rgb(255, 255, 255); border: 1px solid rgb(173, 179, 185); border-radius: 3px; box-shadow: rgba(12, 13, 14, 0.2) 0px 1px 0px, rgb(255, 255, 255) 0px 0px 0px 2px inset; white-space: nowrap; vertical-align: middle; }
.md-comment { color: rgb(162, 127, 3); opacity: 0.6; font-family: var(--monospace); }
code { text-align: left; vertical-align: initial; }
a.md-print-anchor { white-space: pre !important; border-width: initial !important; border-style: none !important; border-color: initial !important; display: inline-block !important; position: absolute !important; width: 1px !important; right: 0px !important; outline: 0px !important; background: 0px 0px !important; text-decoration: initial !important; text-shadow: initial !important; }
.os-windows.monocolor-emoji .md-emoji { font-family: "Segoe UI Symbol", sans-serif; }
.md-diagram-panel > svg { max-width: 100%; }
[lang="flow"] svg, [lang="mermaid"] svg { max-width: 100%; height: auto; }
[lang="mermaid"] .node text { font-size: 1rem; }
table tr th { border-bottom: 0px; }
video { max-width: 100%; display: block; margin: 0px auto; }
iframe { max-width: 100%; width: 100%; border: none; }
.highlight td, .highlight tr { border: 0px; }
mark { background: rgb(255, 255, 0); color: rgb(0, 0, 0); }
.md-html-inline .md-plain, .md-html-inline strong, mark .md-inline-math, mark strong { color: inherit; }
.md-expand mark .md-meta { opacity: 0.3 !important; }
mark .md-meta { color: rgb(0, 0, 0); }
@media print {
  .typora-export h1, .typora-export h2, .typora-export h3, .typora-export h4, .typora-export h5, .typora-export h6 { break-inside: avoid; }
}
.md-diagram-panel .messageText { stroke: none !important; }
.md-diagram-panel .start-state { fill: var(--node-fill); }
.md-diagram-panel .edgeLabel rect { opacity: 1 !important; }
.md-fences.md-fences-math { font-size: 1em; }
.md-fences-advanced:not(.md-focus) { padding: 0px; white-space: nowrap; border: 0px; }
.md-fences-advanced:not(.md-focus) { background: inherit; }
.typora-export-show-outline .typora-export-content { max-width: 1440px; margin: auto; display: flex; flex-direction: row; }
.typora-export-sidebar { width: 300px; font-size: 0.8rem; margin-top: 80px; margin-right: 18px; }
.typora-export-show-outline #write { --webkit-flex:2; flex: 2 1 0%; }
.typora-export-sidebar .outline-content { position: fixed; top: 0px; max-height: 100%; overflow: hidden auto; padding-bottom: 30px; padding-top: 60px; width: 300px; }
@media screen and (max-width: 1024px) {
  .typora-export-sidebar, .typora-export-sidebar .outline-content { width: 240px; }
}
@media screen and (max-width: 800px) {
  .typora-export-sidebar { display: none; }
}
.outline-content li, .outline-content ul { margin-left: 0px; margin-right: 0px; padding-left: 0px; padding-right: 0px; list-style: none; }
.outline-content ul { margin-top: 0px; margin-bottom: 0px; }
.outline-content strong { font-weight: 400; }
.outline-expander { width: 1rem; height: 1.42857rem; position: relative; display: table-cell; vertical-align: middle; cursor: pointer; padding-left: 4px; }
.outline-expander::before { content: ""; position: relative; font-family: Ionicons; display: inline-block; font-size: 8px; vertical-align: middle; }
.outline-item { padding-top: 3px; padding-bottom: 3px; cursor: pointer; }
.outline-expander:hover::before { content: ""; }
.outline-h1 > .outline-item { padding-left: 0px; }
.outline-h2 > .outline-item { padding-left: 1em; }
.outline-h3 > .outline-item { padding-left: 2em; }
.outline-h4 > .outline-item { padding-left: 3em; }
.outline-h5 > .outline-item { padding-left: 4em; }
.outline-h6 > .outline-item { padding-left: 5em; }
.outline-label { cursor: pointer; display: table-cell; vertical-align: middle; text-decoration: none; color: inherit; }
.outline-label:hover { text-decoration: underline; }
.outline-item:hover { border-color: rgb(245, 245, 245); background-color: var(--item-hover-bg-color); }
.outline-item:hover { margin-left: -28px; margin-right: -28px; border-left: 28px solid transparent; border-right: 28px solid transparent; }
.outline-item-single .outline-expander::before, .outline-item-single .outline-expander:hover::before { display: none; }
.outline-item-open > .outline-item > .outline-expander::before { content: ""; }
.outline-children { display: none; }
.info-panel-tab-wrapper { display: none; }
.outline-item-open > .outline-children { display: block; }
.typora-export .outline-item { padding-top: 1px; padding-bottom: 1px; }
.typora-export .outline-item:hover { margin-right: -8px; border-right: 8px solid transparent; }
.typora-export .outline-expander::before { content: "+"; font-family: inherit; top: -1px; }
.typora-export .outline-expander:hover::before, .typora-export .outline-item-open > .outline-item > .outline-expander::before { content: "−"; }
.typora-export-collapse-outline .outline-children { display: none; }
.typora-export-collapse-outline .outline-item-open > .outline-children, .typora-export-no-collapse-outline .outline-children { display: block; }
.typora-export-no-collapse-outline .outline-expander::before { content: "" !important; }
.typora-export-show-outline .outline-item-active > .outline-item .outline-label { font-weight: 700; }
.md-inline-math-container mjx-container { zoom: 0.95; }


.CodeMirror { height: auto; }
.CodeMirror.cm-s-inner { background: inherit; }
.CodeMirror-scroll { overflow: auto hidden; z-index: 3; }
.CodeMirror-gutter-filler, .CodeMirror-scrollbar-filler { background-color: rgb(255, 255, 255); }
.CodeMirror-gutters { border-right: 1px solid rgb(221, 221, 221); background: inherit; white-space: nowrap; }
.CodeMirror-linenumber { padding: 0px 3px 0px 5px; text-align: right; color: rgb(153, 153, 153); }
.cm-s-inner .cm-keyword { color: rgb(119, 0, 136); }
.cm-s-inner .cm-atom, .cm-s-inner.cm-atom { color: rgb(34, 17, 153); }
.cm-s-inner .cm-number { color: rgb(17, 102, 68); }
.cm-s-inner .cm-def { color: rgb(0, 0, 255); }
.cm-s-inner .cm-variable { color: rgb(0, 0, 0); }
.cm-s-inner .cm-variable-2 { color: rgb(0, 85, 170); }
.cm-s-inner .cm-variable-3 { color: rgb(0, 136, 85); }
.cm-s-inner .cm-string { color: rgb(170, 17, 17); }
.cm-s-inner .cm-property { color: rgb(0, 0, 0); }
.cm-s-inner .cm-operator { color: rgb(152, 26, 26); }
.cm-s-inner .cm-comment, .cm-s-inner.cm-comment { color: rgb(170, 85, 0); }
.cm-s-inner .cm-string-2 { color: rgb(255, 85, 0); }
.cm-s-inner .cm-meta { color: rgb(85, 85, 85); }
.cm-s-inner .cm-qualifier { color: rgb(85, 85, 85); }
.cm-s-inner .cm-builtin { color: rgb(51, 0, 170); }
.cm-s-inner .cm-bracket { color: rgb(153, 153, 119); }
.cm-s-inner .cm-tag { color: rgb(17, 119, 0); }
.cm-s-inner .cm-attribute { color: rgb(0, 0, 204); }
.cm-s-inner .cm-header, .cm-s-inner.cm-header { color: rgb(0, 0, 255); }
.cm-s-inner .cm-quote, .cm-s-inner.cm-quote { color: rgb(0, 153, 0); }
.cm-s-inner .cm-hr, .cm-s-inner.cm-hr { color: rgb(153, 153, 153); }
.cm-s-inner .cm-link, .cm-s-inner.cm-link { color: rgb(0, 0, 204); }
.cm-negative { color: rgb(221, 68, 68); }
.cm-positive { color: rgb(34, 153, 34); }
.cm-header, .cm-strong { font-weight: 700; }
.cm-del { text-decoration: line-through; }
.cm-em { font-style: italic; }
.cm-link { text-decoration: underline; }
.cm-error { color: red; }
.cm-invalidchar { color: red; }
.cm-constant { color: rgb(38, 139, 210); }
.cm-defined { color: rgb(181, 137, 0); }
div.CodeMirror span.CodeMirror-matchingbracket { color: rgb(0, 255, 0); }
div.CodeMirror span.CodeMirror-nonmatchingbracket { color: rgb(255, 34, 34); }
.cm-s-inner .CodeMirror-activeline-background { background: inherit; }
.CodeMirror { position: relative; overflow: hidden; }
.CodeMirror-scroll { height: 100%; outline: 0px; position: relative; box-sizing: content-box; background: inherit; }
.CodeMirror-sizer { position: relative; }
.CodeMirror-gutter-filler, .CodeMirror-hscrollbar, .CodeMirror-scrollbar-filler, .CodeMirror-vscrollbar { position: absolute; z-index: 6; display: none; outline: 0px; }
.CodeMirror-vscrollbar { right: 0px; top: 0px; overflow: hidden; }
.CodeMirror-hscrollbar { bottom: 0px; left: 0px; overflow: auto hidden; }
.CodeMirror-scrollbar-filler { right: 0px; bottom: 0px; }
.CodeMirror-gutter-filler { left: 0px; bottom: 0px; }
.CodeMirror-gutters { position: absolute; left: 0px; top: 0px; padding-bottom: 10px; z-index: 3; overflow-y: hidden; }
.CodeMirror-gutter { white-space: normal; height: 100%; box-sizing: content-box; padding-bottom: 30px; margin-bottom: -32px; display: inline-block; }
.CodeMirror-gutter-wrapper { position: absolute; z-index: 4; background: 0px 0px !important; border: none !important; }
.CodeMirror-gutter-background { position: absolute; top: 0px; bottom: 0px; z-index: 4; }
.CodeMirror-gutter-elt { position: absolute; cursor: default; z-index: 4; }
.CodeMirror-lines { cursor: text; }
.CodeMirror pre { border-radius: 0px; border-width: 0px; background: 0px 0px; font-family: inherit; font-size: inherit; margin: 0px; white-space: pre; overflow-wrap: normal; color: inherit; z-index: 2; position: relative; overflow: visible; }
.CodeMirror-wrap pre { overflow-wrap: break-word; white-space: pre-wrap; word-break: normal; }
.CodeMirror-code pre { border-right: 30px solid transparent; width: fit-content; }
.CodeMirror-wrap .CodeMirror-code pre { border-right: none; width: auto; }
.CodeMirror-linebackground { position: absolute; inset: 0px; z-index: 0; }
.CodeMirror-linewidget { position: relative; z-index: 2; overflow: auto; }
.CodeMirror-wrap .CodeMirror-scroll { overflow-x: hidden; }
.CodeMirror-measure { position: absolute; width: 100%; height: 0px; overflow: hidden; visibility: hidden; }
.CodeMirror-measure pre { position: static; }
.CodeMirror div.CodeMirror-cursor { position: absolute; visibility: hidden; border-right: none; width: 0px; }
.CodeMirror div.CodeMirror-cursor { visibility: hidden; }
.CodeMirror-focused div.CodeMirror-cursor { visibility: inherit; }
.cm-searching { background: rgba(255, 255, 0, 0.4); }
span.cm-underlined { text-decoration: underline; }
span.cm-strikethrough { text-decoration: line-through; }
.cm-tw-syntaxerror { color: rgb(255, 255, 255); background-color: rgb(153, 0, 0); }
.cm-tw-deleted { text-decoration: line-through; }
.cm-tw-header5 { font-weight: 700; }
.cm-tw-listitem:first-child { padding-left: 10px; }
.cm-tw-box { border-style: solid; border-right-width: 1px; border-bottom-width: 1px; border-left-width: 1px; border-color: inherit; border-top-width: 0px !important; }
.cm-tw-underline { text-decoration: underline; }
@media print {
  .CodeMirror div.CodeMirror-cursor { visibility: hidden; }
}


:root {
    --side-bar-bg-color: #d9ede5;
    --control-text-color: #6B6B6B;
    --active-file-bg-color: #ecf6f2;
    --active-file-border-color: #6B6B6B;
    --active-file-text-color: #202020;
    --table-even-row-color: #f8fcfa;
    --table-head-color: #d9ede5;
    --deep-theme-color: #4eb289;
    --code-block-bg-color: #0F111A;
}


/*serif*/

/*monospace*/

/*Chinese*/

html {
    font-size: 16px;
}

body {
    font-family: 'Lexend', 'Helvetica', 'Cascadia Code', 'NotoSansSC';
    font-weight: normal;
    line-height: 1.5rem;
    letter-spacing: 0;
    margin: 0;
}

#write {
    max-width: 900px;
    padding: 30px 50px 20px;
}

#write p {
    text-align: left;
}

#write pre.md-meta-block {
    padding: 1rem;
    font-size: 85%;
    line-height: 1.45;
    background-color: #f7f7f7;
    border: 0;
    border-radius: 3px;
    color: #777777;
    margin-top: 0 !important;
}

.md-image>.md-meta {
    color: #777777;
    font-size: 0.9rem;
    font-family: 'Lexend';
    padding: 4px 0;
}

@media print {
    html,
    body {
        font-size: 14px;
    }
    .md-fences {
        line-height: 1.2rem;
    }
    table,
    pre {
        page-break-inside: avoid;
    }
    pre {
        word-wrap: break-word;
    }
}

@page {
    size: A4;
    margin: 8mm 0mm;
}


/*toc*/

.md-toc {
    margin-top: 20px;
    padding-bottom: 20px;
    color: var(--deep-theme-color);
}

a {
    color: var(--deep-theme-color);
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}


/*headers*/

h1,
h2,
h3,
h4,
h5,
h6 {
    display: block;
    font-weight: bold;
}

h1 {
    font-size: 1.8em;
    line-height: 110%;
    margin-top: 0.67em;
    margin-bottom: 0.67em;
}

h2 {
    font-size: 1.5em;
    margin-top: 0.83em;
    margin-bottom: 0.83em;
}

h3 {
    font-size: 1.17em;
    margin-top: 1em;
    margin-bottom: 1em;
}

h4 {
    font-size: 1em;
    margin-top: 1.33em;
    margin-bottom: 1.33em;
}

h5 {
    font-size: 1em;
    margin-top: 1.33em;
    margin-bottom: 1.33em;
    color: #777777;
}

h6 {
    font-size: 1em;
    margin-top: 1.33em;
    margin-bottom: 1.33em;
    color: #adadad;
}

p,
blockquote,
ul,
ol,
dl,
table {
    margin: 0.5rem 0;
}


/*table*/

table {
    border-collapse: collapse;
    padding: 0;
    word-break: initial;
    width: 100%;
}

table tr:nth-child(even) {
    background-color: var(--table-even-row-color);
}

thead {
    background-color: var(--table-head-color);
}

table th {
    text-align: center;
    padding: 6px 13px;
    border: 1px solid var(--table-head-color);
}

table td {
    padding: 6px 13px;
    border: 1px solid var(--table-head-color);
}

table tr {
    padding: 6px 13px;
    border: 1px solid var(--table-head-color);
}


/*blockquote*/

blockquote {
    border-left: 0.2rem solid var(--side-bar-bg-color);
    color: #777777;
    font-family: 'Lexend', 'NotoSansSC';
    font-size: 0.9rem;
    padding-left: 2rem;
}


/*list*/

li p.first {
    display: inline-block;
}

ul,
ol {
    padding-left: 30px;
}

ul:first-child,
ol:first-child {
    margin-top: 0;
}

ul:last-child,
ol:last-child {
    margin-bottom: 0;
}

.md-task-list-item:hover>input:before,
input[type='checkbox']:hover:before {
    opacity: 1;
    transition: 0.5s;
    background-color: var(--side-bar-bg-color);
}

.task-list-item input::before {
    content: "";
    display: inline-block;
    border-radius: 1.1rem;
    vertical-align: middle;
    border: 1.2px solid var(--deep-theme-color);
    background-color: #ffffff;
    width: 1.1rem;
    height: 1.1rem;
    margin-left: -0.1rem;
    margin-right: 0.1rem;
    margin-top: -0.68rem;
}

.task-list-item input:checked::before {
    padding-left: 0.125em;
    content: '✔';
    color: white;
    background-color: var(--deep-theme-color);
    font-size: 0.8rem;
    line-height: 0.95rem;
    margin-top: -0.68rem;
    transition: background-color 200ms ease-in-out;
}

.task-list-done {
    text-decoration: line-through;
    color: #adadad;
}

hr {
    border-style: none;
    border-top-style: solid;
    border-color: #e7e7e7;
    border-width: 1px;
    margin: 2rem 0;
}


/*highlight*/

#write mark {
    background-color: #c7ffe8;
    border-radius: 2px;
    color: black;
    padding: 0 4px;
    margin: 0 2px;
}


/*inline code*/

#write code,
tt {
    padding: 0.6px 4px;
    border-radius: 2px;
    background-color: #f1f1f1;
    font-family: 'Cascadia Code', Consolas, Courier, 'NotoSansSC';
    font-size: small;
    color: var(--code-block-bg-color);
    margin: 0 2px;
}


/*footnote*/

#write .md-footnote {
    color: #777777;
    background-color: #f7f7f7;
}


/*source code mode*/

.cm-s-typora-default .cm-header {
    color: var(--code-block-bg-color);
}

.cm-s-typora-default .cm-link {
    color: var(--deep-theme-color);
}


/*code block*/

#write .md-fences {
    font-size: 1rem;
    margin: 0.2em 0;
    padding: 0.5em;
    border-radius: 3px;
    font-size: 0.9em;
    font-family: 'Cascadia Code', Consolas, Courier, 'NotoSansSC';
    background-color: var(--code-block-bg-color);
    color: #A9B7C6;
    border: none;
    text-shadow: none;
}

.md-fences .code-tooltip {
    background-color: var(--code-block-bg-color);
}


/*
  Name:       material-ocean
  Author:     Mattia Astorino (http://github.com/equinusocio)
  Website:    https://material-theme.site/
*/

.cm-s-inner.CodeMirror {
    background-color: #0F111A;
    color: #8F93A2;
}

.cm-s-inner .CodeMirror-gutters {
    background: #0F111A;
    color: #464B5D;
    border: none;
}

.cm-s-inner .CodeMirror-linenumber {
    color: #464B5D;
}

.cm-s-inner .CodeMirror-guttermarker {
    color: #FFEE80;
}

.cm-s-inner .CodeMirror-guttermarker-subtle {
    color: #D0D0D0;
}


/*
.cm-s-inner .CodeMirror-cursor {
  border-left: 1px solid #FFCC00;
}
.cm-s-inner.cm-fat-cursor .CodeMirror-cursor {
  background-color: #FFCC00 !important;
}
.cm-s-inner .cm-animate-fat-cursor {
  background-color: #FFCC00 !important;
}
*/

.cm-s-inner .CodeMirror-cursor {
    border-left: 1px solid #A9B7C6;
}

.cm-s-inner div.CodeMirror-cursor {
    border-left: 1px solid #ffffff;
}

.cm-s-inner div.CodeMirror-selected {
    background: rgba(113, 124, 180, 0.2);
}

.cm-s-inner.CodeMirror-focused div.CodeMirror-selected {
    background: rgba(113, 124, 180, 0.2);
}

.cm-s-inner .CodeMirror-selected {
    background: #214283 !important;
}

.cm-s-inner .CodeMirror-selectedtext {
    background: #214283 !important;
}

.cm-overlay.CodeMirror-selectedtext {
    background: #B5D6FC !important;
}

.cm-s-inner .CodeMirror-line::selection,
.cm-s-inner .CodeMirror-line>span::selection,
.cm-s-inner .CodeMirror-line>span>span::selection {
    background: rgba(128, 203, 196, 0.2);
}

.cm-s-inner .CodeMirror-line::-moz-selection,
.cm-s-inner .CodeMirror-line>span::-moz-selection,
.cm-s-inner .CodeMirror-line>span>span::-moz-selection {
    background: rgba(128, 203, 196, 0.2);
}


/* .cm-s-inner .CodeMirror-activeline-background {
  background: rgba(0, 0, 0, 0.5);
} */

.cm-s-inner .cm-keyword {
    color: #C792EA;
}

.cm-s-inner .cm-operator {
    color: #89DDFF;
}

.cm-s-inner .cm-variable-2 {
    color: #EEFFFF;
}

.cm-s-inner .cm-variable-3,
.cm-s-inner .cm-type {
    color: #f07178;
}

.cm-s-inner .cm-builtin {
    color: #FFCB6B;
}

.cm-s-inner .cm-atom {
    color: #F78C6C;
}

.cm-s-inner .cm-number {
    color: #FF5370;
}

.cm-s-inner .cm-def {
    color: #82AAFF;
}

.cm-s-inner .cm-string {
    color: #C3E88D;
}

.cm-s-inner .cm-string-2 {
    color: #f07178;
}

.cm-s-inner .cm-comment {
    color: #585d6d;
}

.cm-s-inner .cm-variable {
    color: #f07178;
}

.cm-s-inner .cm-tag {
    color: #FF5370;
}

.cm-s-inner .cm-meta {
    color: #FFCB6B;
}

.cm-s-inner .cm-attribute {
    color: #C792EA;
}

.cm-s-inner .cm-property {
    color: #C792EA;
}

.cm-s-inner .cm-qualifier {
    color: #DECB6B;
}

.cm-s-inner .cm-variable-3,
.cm-s-inner .cm-type {
    color: #DECB6B;
}

.cm-s-inner .cm-error {
    color: rgba(255, 255, 255, 1.0);
    background-color: #FF5370;
}

.cm-s-inner .CodeMirror-matchingbracket {
    text-decoration: underline;
    color: white !important;
}


</style><title>README</title>
</head>
<body class='typora-export os-windows'><div class='typora-export-content'>
<div id='write'  class=''><h1 id='github-profile'><span>GitHub Profile</span></h1><h2 id='about-me'><strong><span>About me</span></strong></h2><p><span>I am an undergraduate in mathematics and theoretical computer science with a minor in cybersecurity who intends to be a researcher and pursue a PhD. I predominantly prefer C, along with object-oriented programming languages such as:</span></p><ul><li><span>Java,</span></li><li><span>Python,</span></li><li><span>Ruby.</span></li></ul><p><span>However, I am also acquainted with Assembly (ASM, FASM) and just a little functional programming in Haskell. My academic and research interests are expansive, and they encompass the following:</span></p><ol start='' ><li><span>Analysis of Algorithms,</span></li><li><span>Computational Complexity,</span></li><li><span>Computational Number Theory,</span></li><li><span>Cryptography and Cryptanalysis,</span></li><li><span>Design and Security Analysis of Compilers,</span></li><li><span>Functional Programming and Monads,</span></li><li><span>Mathematical Theory of Privacy,</span></li><li><span>Privacy Using Machine Learning and Deep Learning,</span></li><li><span>Quantum Resilient Cryptography.</span></li></ol><p><span>I am also a fervent Linux devotee with strong opinions about digital anonymity and confidentiality. And on top of all of that, I am an open source fanatic and a huge proponent of digital privacy and anonymity. Nearly every single day, I have been using LaTeX for systematic note-taking and documentation, Docker for getting specific tool chains and compilers to work properly, git for source and revision control, VS Code or Jupyter Lab for programming and algorithm implementation, and Arch Linux as my operating system because it offers flexibility and customizability, and the package manager </span><code>pacman</code><span> is just fantastic.</span></p><p><span>I usually sign my documents and important work, including my GitHub commits, with the key given below. Feel free to use this for signing and sending me documents.</span></p><h3 id='my-favourite-program'><span>My favourite program</span></h3><pre class="md-fences md-end-block ty-contain-cm modeLoaded" spellcheck="false" lang="haskell"><div class="CodeMirror cm-s-inner cm-s-null-scroll CodeMirror-wrap" lang="haskell"><div style="overflow: hidden; position: relative; width: 3px; height: 0px; top: 10px; left: 4px;"><textarea autocorrect="off" autocapitalize="off" spellcheck="false" tabindex="0" style="position: absolute; bottom: -1em; padding: 0px; width: 1000px; height: 1em; outline: none;"></textarea></div><div class="CodeMirror-scrollbar-filler" cm-not-content="true"></div><div class="CodeMirror-gutter-filler" cm-not-content="true"></div><div class="CodeMirror-scroll" tabindex="-1"><div class="CodeMirror-sizer" style="margin-left: 0px; margin-bottom: 0px; border-right-width: 0px; padding-right: 0px; padding-bottom: 0px;"><div style="position: relative; top: 0px;"><div class="CodeMirror-lines" role="presentation"><div role="presentation" style="position: relative; outline: none;"><div class="CodeMirror-measure"><pre><span>xxxxxxxxxx</span></pre></div><div class="CodeMirror-measure"></div><div style="position: relative; z-index: 1;"></div><div class="CodeMirror-code" role="presentation"><div class="CodeMirror-activeline" style="position: relative;"><div class="CodeMirror-activeline-background CodeMirror-linebackground"></div><div class="CodeMirror-gutter-background CodeMirror-activeline-gutter" style="left: 0px; width: 0px;"></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-variable">fibonacci</span> <span class="cm-keyword">::</span> <span class="cm-builtin">Integer</span> <span class="cm-keyword">-&gt;</span> <span class="cm-builtin">Integer</span></span></pre></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-variable">fibonacci</span> <span class="cm-number">0</span> <span class="cm-keyword">=</span> <span class="cm-number">1</span></span></pre><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-variable">fibonacci</span> <span class="cm-number">1</span> <span class="cm-keyword">=</span> <span class="cm-number">1</span></span></pre><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-variable">fibonacci</span> <span class="cm-variable">x</span> <span class="cm-keyword">=</span> <span class="cm-variable">fibonacci</span> (<span class="cm-variable">x</span><span class="cm-builtin">-</span><span class="cm-number">1</span>) <span class="cm-builtin">+</span> <span class="cm-variable">fibonacci</span> (<span class="cm-variable">x</span><span class="cm-builtin">-</span><span class="cm-number">2</span>)</span></pre></div></div></div></div></div><div style="position: absolute; height: 0px; width: 1px; border-bottom: 0px solid transparent; top: 96px;"></div><div class="CodeMirror-gutters" style="display: none; height: 96px;"></div></div></div></pre><p><span>I&#39;m presently concentrating on the following initiatives:</span></p><ul><li><span>Lightweight Cryptography for CPS: State of the Art,</span></li><li><span>Cryptography Essentials for Cybersecurity: Fundamentals And Applications,</span></li><li><span>Literature Review: Password Generation Methods for Secure Authentications.</span></li></ul><p><span>I do have a bibliography that may be of relevance to students and researchers; it includes books and scientific journals on mathematics, theoretical computer science, and cryptography. It&#39;s obtainable right </span><a href='https://gist.github.com/datta-agni/1d5ae6df198320c8f942f78aed3479aa'><span>here.</span></a></p><p><span>Typically, my interests involve deep lying theoretical and mathematical issues such as Elliptical Curve Cryptography, Lattice-based Cryptography, privacy-preserving machine learning, and NP Completeness of algorithms. Although occasionally I work with applied technologies, especially with applied cryptography, such as cryptographic implementation in CPS, IoT, so on and so forth.</span></p><p><span>💡 </span><strong><span>My PGP Public Key can be found </span><a href='https://keys.openpgp.org/vks/v1/by-fingerprint/034FA3D4FD4067E5BCF30B6FCF8D56CABE52E5E9'><span>here.</span></a></strong></p><p><span>I usually signs my documents and important work including my GitHub commits with this key. Feel free to use this for signing and sending me documents.</span></p><h3 id='familiar-with-the-following'><span>Familiar with the following</span></h3><p><img src="https://camo.githubusercontent.com/92ba876280cf504a26b41f7a0dc10a27c793613763b2c32bfcdcd2acb5453d12/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f41646f62652532304c69676874726f6f6d2d3331413846463f7374796c653d666f722d7468652d6261646765266c6f676f3d41646f62652532304c69676874726f6f6d266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/92ba876280cf504a26b41f7a0dc10a27c793613763b2c32bfcdcd2acb5453d12/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f41646f62652532304c69676874726f6f6d2d3331413846463f7374796c653d666f722d7468652d6261646765266c6f676f3d41646f62652532304c69676874726f6f6d266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/32aa15cf5066ee9368cb35ef220ca4760d11eb0513688ca96c28d21298d845d0/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f41646f62652532304c69676874726f6f6d253230436c61737369632d3331413846462e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d41646f62652532304c69676874726f6f6d253230436c6173736963266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/32aa15cf5066ee9368cb35ef220ca4760d11eb0513688ca96c28d21298d845d0/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f41646f62652532304c69676874726f6f6d253230436c61737369632d3331413846462e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d41646f62652532304c69676874726f6f6d253230436c6173736963266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/5b7886225855c2c5ac8bcc15effcb289c238c597680d61c24e5e7541af59ee10/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f416e64726f69642d3344444338343f7374796c653d666f722d7468652d6261646765266c6f676f3d616e64726f6964266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/5b7886225855c2c5ac8bcc15effcb289c238c597680d61c24e5e7541af59ee10/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f416e64726f69642d3344444338343f7374796c653d666f722d7468652d6261646765266c6f676f3d616e64726f6964266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/044d53b239f41a8f410c0400675aef3adad3d5577e6bac216e06d9dd8cb224c0/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f417263682532304c696e75782d3137393344313f6c6f676f3d617263682d6c696e7578266c6f676f436f6c6f723d666666267374796c653d666f722d7468652d6261646765" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/044d53b239f41a8f410c0400675aef3adad3d5577e6bac216e06d9dd8cb224c0/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f417263682532304c696e75782d3137393344313f6c6f676f3d617263682d6c696e7578266c6f676f436f6c6f723d666666267374796c653d666f722d7468652d6261646765">
<img src="https://camo.githubusercontent.com/fc9031b590e87805c5cc752a03e2685815df3b989c853b649c25eb77bccabdb2/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f41746f6d2d2532333636353935432e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d61746f6d266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/fc9031b590e87805c5cc752a03e2685815df3b989c853b649c25eb77bccabdb2/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f41746f6d2d2532333636353935432e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d61746f6d266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/2105368502570bcee9cd4877f24044e5d44df23f4063aff455e6fdae6ae0be00/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f41756461636974792d3030303043433f7374796c653d666f722d7468652d6261646765266c6f676f3d6175646163697479266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/2105368502570bcee9cd4877f24044e5d44df23f4063aff455e6fdae6ae0be00/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f41756461636974792d3030303043433f7374796c653d666f722d7468652d6261646765266c6f676f3d6175646163697479266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/5859172b2d0854f4d70d35118ae1fbb8d92f967ea654f1bb1bdae4a346d03926/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f632d2532333030353939432e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d63266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/5859172b2d0854f4d70d35118ae1fbb8d92f967ea654f1bb1bdae4a346d03926/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f632d2532333030353939432e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d63266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/94c5a32b53c1771bd1a163fe0523aee22b624e1d613ec984e52686cda1cdb2bd/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f44656269616e2d4437304135333f7374796c653d666f722d7468652d6261646765266c6f676f3d64656269616e266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/94c5a32b53c1771bd1a163fe0523aee22b624e1d613ec984e52686cda1cdb2bd/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f44656269616e2d4437304135333f7374796c653d666f722d7468652d6261646765266c6f676f3d64656269616e266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/6b7f701cf0bea42833751b754688f1a27b6090fdf90bf2b226addff01be817f0/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f636b65722d2532333064623765642e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d646f636b6572266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/6b7f701cf0bea42833751b754688f1a27b6090fdf90bf2b226addff01be817f0/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f646f636b65722d2532333064623765642e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d646f636b6572266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/779e1e8de67b6f76e99d72dc5f758af3c80506064a7833fa5da4852cd77e3620/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4665646f72612d3239343137323f7374796c653d666f722d7468652d6261646765266c6f676f3d6665646f7261266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/779e1e8de67b6f76e99d72dc5f758af3c80506064a7833fa5da4852cd77e3620/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4665646f72612d3239343137323f7374796c653d666f722d7468652d6261646765266c6f676f3d6665646f7261266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/ec0d32e85caf4723d5182a75338c89f85a2c3679aed0c46c9ee9fd1c8dc2a316/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6769742d2532334630353033332e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d676974266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/ec0d32e85caf4723d5182a75338c89f85a2c3679aed0c46c9ee9fd1c8dc2a316/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6769742d2532334630353033332e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d676974266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/f6d50128cb007f85916b7a899da5d94f654dce35a37331c8d28573aef46f4274/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6769746875622d2532333132313031312e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/f6d50128cb007f85916b7a899da5d94f654dce35a37331c8d28573aef46f4274/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6769746875622d2532333132313031312e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/032b1bba6a73d05174d2dd34660060438667f4311d465ef7136e0c9e19b645c2/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4861736b656c6c2d3565353038363f7374796c653d666f722d7468652d6261646765266c6f676f3d6861736b656c6c266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/032b1bba6a73d05174d2dd34660060438667f4311d465ef7136e0c9e19b645c2/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4861736b656c6c2d3565353038363f7374796c653d666f722d7468652d6261646765266c6f676f3d6861736b656c6c266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/bae7086a19b2448e35827886725754efab56b29eeb72cc5d77e1eec3a71eed81/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f496e6b73636170652d6530653065303f7374796c653d666f722d7468652d6261646765266c6f676f3d696e6b7363617065266c6f676f436f6c6f723d303830413133" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/bae7086a19b2448e35827886725754efab56b29eeb72cc5d77e1eec3a71eed81/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f496e6b73636170652d6530653065303f7374796c653d666f722d7468652d6261646765266c6f676f3d696e6b7363617065266c6f676f436f6c6f723d303830413133">
<img src="https://camo.githubusercontent.com/6cbecd63a9a8f83ee186885c446938820ffa8304942a284ee6e1e2acb2bfd822/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6a6176612d2532334544384230302e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6a617661266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/6cbecd63a9a8f83ee186885c446938820ffa8304942a284ee6e1e2acb2bfd822/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6a6176612d2532334544384230302e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6a617661266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/75251632e9c74475dfb9c8a4f17b34792226384fe87ff456cb8603b4e94a15bf/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4a7570797465722d4633373632362e7376673f267374796c653d666f722d7468652d6261646765266c6f676f3d4a757079746572266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/75251632e9c74475dfb9c8a4f17b34792226384fe87ff456cb8603b4e94a15bf/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4a7570797465722d4633373632362e7376673f267374796c653d666f722d7468652d6261646765266c6f676f3d4a757079746572266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/a0729ab382adb05cbaa5700200f3092bf7726fc4f18e19338ac43ab27025a5c8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4b616c695f4c696e75782d3535374339343f7374796c653d666f722d7468652d6261646765266c6f676f3d6b616c692d6c696e7578266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/a0729ab382adb05cbaa5700200f3092bf7726fc4f18e19338ac43ab27025a5c8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4b616c695f4c696e75782d3535374339343f7374796c653d666f722d7468652d6261646765266c6f676f3d6b616c692d6c696e7578266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/87f8b4bfb89380f96a10d753be68a6d8d214160f908af4487557b20083ffc601/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c615465582d3437413134313f7374796c653d666f722d7468652d6261646765266c6f676f3d4c61546558266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/87f8b4bfb89380f96a10d753be68a6d8d214160f908af4487557b20083ffc601/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c615465582d3437413134313f7374796c653d666f722d7468652d6261646765266c6f676f3d4c61546558266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/878e15b4f7576e844856dc60d855ba0587d3d2bc56211fbe69734ebccb13b068/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c696e75782d4643433632343f7374796c653d666f722d7468652d6261646765266c6f676f3d6c696e7578266c6f676f436f6c6f723d626c61636b" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/878e15b4f7576e844856dc60d855ba0587d3d2bc56211fbe69734ebccb13b068/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c696e75782d4643433632343f7374796c653d666f722d7468652d6261646765266c6f676f3d6c696e7578266c6f676f436f6c6f723d626c61636b">
<img src="https://camo.githubusercontent.com/a44844ce4d3bf26f4685d5ae0e0fab359cdeca62ad71c675d3d89fd30f418665/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6d61726b646f776e2d2532333030303030302e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6d61726b646f776e266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/a44844ce4d3bf26f4685d5ae0e0fab359cdeca62ad71c675d3d89fd30f418665/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6d61726b646f776e2d2532333030303030302e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6d61726b646f776e266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/a1c5e9056e3be1e1058d8517b025af60f61f75395a78245776db71a7703aff9c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6e756d70792d2532333031333234332e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6e756d7079266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/a1c5e9056e3be1e1058d8517b025af60f61f75395a78245776db71a7703aff9c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6e756d70792d2532333031333234332e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6e756d7079266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/cf56166218460a063162d778334b2489fc8c568fa9b330689850e9a7eed9be72/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6e67696e782d2532333030393633392e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6e67696e78266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/cf56166218460a063162d778334b2489fc8c568fa9b330689850e9a7eed9be72/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6e67696e782d2532333030393633392e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6e67696e78266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/c676b5f90a1650624a0a9832d7954edda1db39ad3347d90c8c51e88ff2f92252/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d4646443433423f7374796c653d666f722d7468652d6261646765266c6f676f3d707974686f6e266c6f676f436f6c6f723d6461726b677265656e" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/c676b5f90a1650624a0a9832d7954edda1db39ad3347d90c8c51e88ff2f92252/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d4646443433423f7374796c653d666f722d7468652d6261646765266c6f676f3d707974686f6e266c6f676f436f6c6f723d6461726b677265656e">
<img src="https://camo.githubusercontent.com/5b61735c54b91b851198d6de978a3ff3f3f9b5c2428bd5ed7f28ced1c93a181c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f727562792d2532334343333432442e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d72756279266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/5b61735c54b91b851198d6de978a3ff3f3f9b5c2428bd5ed7f28ced1c93a181c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f727562792d2532334343333432442e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d72756279266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/e70497c8ce44be13c11100d9ca6cd835a78ef716df5b4385c44ada096dec357a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f53636950792d2532333043353541352e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d7363697079266c6f676f436f6c6f723d257768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/e70497c8ce44be13c11100d9ca6cd835a78ef716df5b4385c44ada096dec357a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f53636950792d2532333043353541352e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d7363697079266c6f676f436f6c6f723d257768697465">
<img src="https://camo.githubusercontent.com/aca8077e4bfa77bc5469b4691a9f649a1e22ea5a3271f82bb09dbc7cff80bf4c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5368656c6c5f5363726970742d3132313031313f7374796c653d666f722d7468652d6261646765266c6f676f3d676e752d62617368266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/aca8077e4bfa77bc5469b4691a9f649a1e22ea5a3271f82bb09dbc7cff80bf4c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5368656c6c5f5363726970742d3132313031313f7374796c653d666f722d7468652d6261646765266c6f676f3d676e752d62617368266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/d6de31463470dd4540e7ece7849e6d38d423825f113ea4ae639f4dcfd0392d82/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5562756e74752d4539353432303f7374796c653d666f722d7468652d6261646765266c6f676f3d7562756e7475266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/d6de31463470dd4540e7ece7849e6d38d423825f113ea4ae639f4dcfd0392d82/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5562756e74752d4539353432303f7374796c653d666f722d7468652d6261646765266c6f676f3d7562756e7475266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/d8d68d0ff3e31f17649ff3a86c30f95f90578a16c55e2cc34f09566a9083d0b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f56697375616c53747564696f436f64652d3030373864372e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d76697375616c2d73747564696f2d636f6465266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/d8d68d0ff3e31f17649ff3a86c30f95f90578a16c55e2cc34f09566a9083d0b7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f56697375616c53747564696f436f64652d3030373864372e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d76697375616c2d73747564696f2d636f6465266c6f676f436f6c6f723d7768697465"></p><h3 id='i-support-'><strong><span>I support !</span></strong></h3><p><a href='https://www.freecodecamp.org/'><img src="https://camo.githubusercontent.com/387b0577360959651f848bb2a3c54ed5eda1815f0cb0f67ebb08ac72e5ebead1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f46726565636f646563616d702d2532333132332e7376673f267374796c653d666f722d7468652d6261646765266c6f676f3d66726565636f646563616d70266c6f676f436f6c6f723d677265656e" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/387b0577360959651f848bb2a3c54ed5eda1815f0cb0f67ebb08ac72e5ebead1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f46726565636f646563616d702d2532333132332e7376673f267374796c653d666f722d7468652d6261646765266c6f676f3d66726565636f646563616d70266c6f676f436f6c6f723d677265656e"></a>
<a href='https://www.torproject.org/'><img src="https://camo.githubusercontent.com/ccc2f3dae6dcd65277bbd8b0b608f646a83e1193326d23fb23e6579fc5386515/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f546f722d3744343639383f7374796c653d666f722d7468652d6261646765266c6f676f3d546f722d42726f77736572266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/ccc2f3dae6dcd65277bbd8b0b608f646a83e1193326d23fb23e6579fc5386515/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f546f722d3744343639383f7374796c653d666f722d7468652d6261646765266c6f676f3d546f722d42726f77736572266c6f676f436f6c6f723d7768697465"></a></p><h2 id='github-statistics'><strong><span>GitHub Statistics</span></strong></h2><p><img src="https://camo.githubusercontent.com/0c49e18c14e94f5a97f88441c574b21ebc734d06ca8dd8342147e210faf6d204/68747470733a2f2f61637469766974792d67726170682e6865726f6b756170702e636f6d2f67726170683f757365726e616d653d64617474612d61676e69267468656d653d636861727472657573652d6461726b266c696e653d32343239326526706f696e743d32343239326526617265613d7472756526686964655f626f726465723d74727565" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/0c49e18c14e94f5a97f88441c574b21ebc734d06ca8dd8342147e210faf6d204/68747470733a2f2f61637469766974792d67726170682e6865726f6b756170702e636f6d2f67726170683f757365726e616d653d64617474612d61676e69267468656d653d636861727472657573652d6461726b266c696e653d32343239326526706f696e743d32343239326526617265613d7472756526686964655f626f726465723d74727565"></p><p><img src="https://camo.githubusercontent.com/a176d7f8b4d592718152cce07ac6bcc6e241a7364f1253f05a8f87871f881355/68747470733a2f2f6769746875622d726561646d652d73747265616b2d73746174732e6865726f6b756170702e636f6d2f3f757365723d64617474612d61676e69267468656d653d636861727472657573652d6461726b26626f7264" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/a176d7f8b4d592718152cce07ac6bcc6e241a7364f1253f05a8f87871f881355/68747470733a2f2f6769746875622d726561646d652d73747265616b2d73746174732e6865726f6b756170702e636f6d2f3f757365723d64617474612d61676e69267468656d653d636861727472657573652d6461726b26626f7264"></p><p><img src="https://camo.githubusercontent.com/0d474e4542335fe62b3ebaf986f5da31029b0de1a19a7f13102ce65f1c89345c/68747470733a2f2f6769746875622d726561646d652d73746174732e76657263656c2e6170702f6170693f757365726e616d653d64617474612d61676e692673686f775f69636f6e733d74727565267468656d653d636861727472657573652d6461726b" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/0d474e4542335fe62b3ebaf986f5da31029b0de1a19a7f13102ce65f1c89345c/68747470733a2f2f6769746875622d726561646d652d73746174732e76657263656c2e6170702f6170693f757365726e616d653d64617474612d61676e692673686f775f69636f6e733d74727565267468656d653d636861727472657573652d6461726b"></p><p><img src="https://camo.githubusercontent.com/3ecb111ba8d4fc979977f3fbb1e6da4dd52bd308c3a76e752bcc897f84f9caf4/68747470733a2f2f6769746875622d726561646d652d73746174732e76657263656c2e6170702f6170692f746f702d6c616e67732f3f757365726e616d653d64617474612d61676e69266c61796f75743d636f6d70616374267468656d653d636861727472657573652d6461726b" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/3ecb111ba8d4fc979977f3fbb1e6da4dd52bd308c3a76e752bcc897f84f9caf4/68747470733a2f2f6769746875622d726561646d652d73746174732e76657263656c2e6170702f6170692f746f702d6c616e67732f3f757365726e616d653d64617474612d61676e69266c61796f75743d636f6d70616374267468656d653d636861727472657573652d6461726b"></p><h2 id='connect-with-me'><strong><span>Connect with me</span></strong></h2><p><a href='https://www.linkedin.com/in/dattagni/'><img src="https://camo.githubusercontent.com/5fd5ee86d78bc2e283325b5f953f1330cb3cff43346ac98673ea6b45dfc07360/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c696e6b6564696e2d2532333030373742352e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6c696e6b6564696e266c6f676f436f6c6f723d7768697465266c696e6b3d68747470733a2f2f7777772e6c696e6b6564696e2e636f6d2f696e2f6461747461676e69" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/5fd5ee86d78bc2e283325b5f953f1330cb3cff43346ac98673ea6b45dfc07360/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c696e6b6564696e2d2532333030373742352e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6c696e6b6564696e266c6f676f436f6c6f723d7768697465266c696e6b3d68747470733a2f2f7777772e6c696e6b6564696e2e636f6d2f696e2f6461747461676e69"></a>
<a href='https://medium.com/@dattadunga'><img src="https://camo.githubusercontent.com/62d98afe4d45ed25a862d0fd48c5f92261372f39809041493204e0387ce92a8f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d656469756d2d2532333030303030302e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d4d656469756d266c6f676f436f6c6f723d7768697465266c696e6b3d68747470733a2f2f6d656469756d2e636f6d2f40646174746164756e6761" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/62d98afe4d45ed25a862d0fd48c5f92261372f39809041493204e0387ce92a8f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d656469756d2d2532333030303030302e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d4d656469756d266c6f676f436f6c6f723d7768697465266c696e6b3d68747470733a2f2f6d656469756d2e636f6d2f40646174746164756e6761"></a></p><h2 id='my-profiles'><strong><span>My Profiles</span></strong></h2><p><a href='https://www.researchgate.net/profile/Agni-Datta-2'><img src="https://camo.githubusercontent.com/69dca1771dfdd234091ab67f8240d000559c1aa9b1f9cd9f9a6e2604c67afc2d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5265736561726368476174652d3030434342423f7374796c653d666f722d7468652d6261646765266c6f676f3d526573656172636847617465266c6f676f436f6c6f723d7768697465" referrerpolicy="no-referrer" alt="https://camo.githubusercontent.com/69dca1771dfdd234091ab67f8240d000559c1aa9b1f9cd9f9a6e2604c67afc2d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5265736561726368476174652d3030434342423f7374796c653d666f722d7468652d6261646765266c6f676f3d526573656172636847617465266c6f676f436f6c6f723d7768697465"></a></p><h3 id='agni-datta'><strong><span>Agni Datta</span></strong></h3><blockquote><p><span>3rd-year Student of Theoretical Computer Science with a minor in Cyber-Security,</span>
<span>SCSE, Vellore Institute of Technology, Bhopal</span></p></blockquote><p><strong><span>University ID:</span></strong><span> </span><a href='mailto:agni.datta2020@vitbhopal.ac.in'><span>agni.datta2020@vitbhopal.ac.in</span></a></p><p><strong><span>Personal ID:</span></strong><span> </span><a href='mailto:dattadunga@gmail.com'><span>dattadunga@gmail.com</span></a></p><p><strong><span>PGP Key</span></strong><span> can be found </span><a href='https://tinyurl.com/agnidatta-pgpkey'><span>here.</span></a></p><p>&nbsp;</p></div></div>
</body>
</html>
