
XWIKI MULTIPAGE EXPORT 
----------------------

Author: XWiki SAS sponsored by a client
Licence: LGPL licence


The XWiki MultiPage Export is an XWiki application allowing to export multiple pages to PDF or XAR.
It particularly allows to create a list of pages to export and then run the export.

It also allows to automatically concatenate a page with it's childrens to allow to view it in HTML or export it to PDF in one big report.

To build this plugin use maven and install the jar in webapps/xwiki/WEB-INF/lib
Update xwiki.cfg's plugin line with:

com.xpn.xwiki.plugin.collection.CollectionPlugin

After build of the XAR import it in your XWiki installation and visit MultiPageExport.Install to finish the install.

The files pdfmulti.vm and printmulti.vm are also needed in the templates directory or in a skin.

See http://extensions.xwiki.org/xwiki/bin/view/Extension/Multipage+Export+Application for more information.
