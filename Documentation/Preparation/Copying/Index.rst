
.. include:: ../../Includes.txt


.. _copying-template:

Copying the template files to the right place
"""""""""""""""""""""""""""""""""""""""""""""

Now you have the extracted files in your file system. They reside
relative to the root folder where you installed TYPO3 in the subfolder
:file:`typo3conf/ext/doc_tut_templating/Resources/Private/Template`.

Get that :file:`Template` folder and copy it with all its contents
to :file:`fileadmin/template/`.


.. _copying-template-page-structure:

Creating a page structure
~~~~~~~~~~~~~~~~~~~~~~~~~

We will now create some pages inside TYPO3. These pages are helpful, when you
later want to check, if TYPO3 uses the instructions in the TypoScript template
as we want it to use them. When you created some pages and subpages, you
will later be able to check if TYPO3 creates the desired output. After you have
configured the menu in the TypoScript template, the structure of these pages
should be visible in the menu. If you put some content in some of these pages
in TYPO3, you will also be able to see this content once you have configured
the corresponding part of the TypoScript template.
