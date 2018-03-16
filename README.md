# Render PDF Images in Oxygen Author Mode

Oxygen XML Editor/Author does not render PDF images by default in the Author page, unless you manually add the Apache PDFBox library by following the procedure described here:
https://www.oxygenxml.com/doc/versions/18.1/ug-editor/tasks/installing-pdf-library.html

This plugin represents an alternate method to the procedure mentioned above. It contributes the libraries necessary for enabling Oxygen to render PDF images in the Author page.

To install it you can copy the `oxygenxml.pdfimage` folder to `OXYGEN_INSTALL_DIR/plugins` or use the following procedure within Oxygem XML Editor/Author:

1. Go to **Help->Install new add-ons** to open an add-on selection dialog box.
2. Enter or paste https://raw.githubusercontent.com/oxygenxml/oxygenxml.pdfimage/master/addon.xml in the **Show add-ons from** field.
3. Select the **PDF Image Rendering** add-on and click **Next**.
4. Select the **I accept all terms of the end user license agreement** option and click **Finish**.
5. Restart the application.

Result: The Apache PDFBox libraries are now contributed to the Oxygen installation directory and you should be able to see PDF images in Author mode.

Copyright and License
---------------------
Copyright 2018 Syncro Soft SRL.

This project is licensed under [Apache License 2.0](https://github.com/oxygenxml/oxygen-pdf-image/blob/master/LICENSE)
