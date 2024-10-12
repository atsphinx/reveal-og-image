========================
atsphinx-reveal-og-image
========================

Generate ``og:image`` content using Reveal.js

Overview
========

This is Sphinx-extension to generate image contents for ``og:image``.

Images are generated from title of documents and project name
using Reveal.js presentation with Playwright.

.. note:: Installation size is large although only purpose of generating images.

Getting started
===============

.. code:: console

   pip install atsphinx-reveal-og-image

.. code:: python

   extensions = [
       ...,  # Your extensions
       "atsphinx.reveal_og_image",
   ]

.. This is plan.

   When you build document, this generates images into ``BUILD_DIR/_images/og-image/{document-name}.png``
