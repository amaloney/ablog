ABlog v0.7 released
===================

.. post:: May 3, 2015
   :author: Ahmet
   :category: Release
   :location: Denizli


ABlog v0.7.0 is released to fix the long standing :issue:`1` related to
pickling of Sphinx build environment on Read The Docs. Improvements
also resolved issues with using LaTeX builder, improved cross-referencing
for non-html builders.


ABlog v0.7.1 released
---------------------

.. post:: Jun 15, 2015
   :author: Ahmet
   :category: Release
   :location: SF

ABlog v0.7.1 is released to fix Python 3 import issues in :command:`ablog serve` command.


ABlog v0.7.2 released
---------------------

.. post:: Jun 15, 2015
   :author: Ahmet
   :category: Release
   :location: SF

ABlog v0.7.2 is released to prevent potential issues with Disqus thread URLs
by requiring :confval:`disqus_shortname` and :confval:`blog_baseurl`
to be specified together for Disqus integration.