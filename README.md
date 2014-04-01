wisski_book_import
==================

An experimental module that splits an XML-encoded text into several WissKI instances
tied together in a Drupal book.

This module was written to import large text files encoded in TEI. It will allow you to
specify the set of elements that constitute the sections to be imported as instances by
an XPath. Text outside of these nodes will be skipped! You can further specify XPaths
to the title of each section and to the book title.

This module depends on the book module: The instance for the whole text is at the same
time a book, the section instances are pages of that book. This allows the use of the
book chapter navigation bar.
