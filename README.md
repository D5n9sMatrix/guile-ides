<!DOCTYPE html>
<!-- saved from url=(0080)https://www.gnu.org/software/emacs/manual/html_node/elisp/Programming-Types.html -->
<html><!-- Created by GNU Texinfo 7.0.3, https://www.gnu.org/software/texinfo/ --><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<title>Programming Types (GNU Emacs Lisp Reference Manual)</title>

<meta name="description" content="Programming Types (GNU Emacs Lisp Reference Manual)">
<meta name="keywords" content="Programming Types (GNU Emacs Lisp Reference Manual)">
<meta name="resource-type" content="document">
<meta name="distribution" content="global">
<meta name="Generator" content="makeinfo">
<meta name="viewport" content="width=device-width,initial-scale=1">

<link rev="made" href="mailto:bug-gnu-emacs@gnu.org">
<link rel="icon" type="image/png" href="https://www.gnu.org/graphics/gnu-head-mini.png">
<meta name="ICBM" content="42.256233,-71.006581">
<meta name="DC.title" content="gnu.org">
<style type="text/css">
@import url('/software/emacs/manual.css');
</style>
</head>

<body lang="en">
<div class="section-level-extent" id="Programming-Types">
<div class="nav-panel">
<p>
Next: <a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Editing-Types.html" accesskey="n" rel="next">Editing Types</a>, Previous: <a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Comments.html" accesskey="p" rel="prev">Comments</a>, Up: <a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Lisp-Data-Types.html" accesskey="u" rel="up">Lisp Data Types</a> &nbsp; [<a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/index.html#SEC_Contents" title="Table of contents" rel="contents">Contents</a>][<a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Index.html" title="Index" rel="index">Index</a>]</p>
</div>
<hr>
<h3 class="section" id="Programming-Types-1">2.4 Programming Types</h3>
<a class="index-entry-id" id="index-programming-types"></a>

<p>There are two general categories of types in Emacs Lisp: those having
to do with Lisp programming, and those having to do with editing.  The
former exist in many Lisp implementations, in one form or another.  The
latter are unique to Emacs Lisp.
</p>

<ul class="mini-toc">
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Integer-Type.html" accesskey="1">Integer Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Floating_002dPoint-Type.html" accesskey="2">Floating-Point Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Character-Type.html" accesskey="3">Character Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Symbol-Type.html" accesskey="4">Symbol Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Sequence-Type.html" accesskey="5">Sequence Types</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Cons-Cell-Type.html" accesskey="6">Cons Cell and List Types</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Array-Type.html" accesskey="7">Array Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/String-Type.html" accesskey="8">String Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Vector-Type.html" accesskey="9">Vector Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Char_002dTable-Type.html">Char-Table Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Bool_002dVector-Type.html">Bool-Vector Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Hash-Table-Type.html">Hash Table Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Function-Type.html">Function Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Macro-Type.html">Macro Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Primitive-Function-Type.html">Primitive Function Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Byte_002dCode-Type.html">Byte-Code Function Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Record-Type.html">Record Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Type-Descriptors.html">Type Descriptors</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Autoload-Type.html">Autoload Type</a></li>
<li><a href="https://www.gnu.org/software/emacs/manual/html_node/elisp/Finalizer-Type.html">Finalizer Type</a></li>
</ul>
</div>





</body></html>