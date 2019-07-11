**Excel Workbook View**
==============================

[![ExcelView Screenshot](/images/readme/image1.png)](http://stdm.gltn.net/)

The ExcelWorkView is a PyQt4-based widget that enables the browsing of Excel (*.xls or *.xlsx) files. It provides a simple and familiar Excel-like interface for browsing one or more worksheets in an Excel file.

Key features include:
* Vertical and horizontal (sequential uppercase) headers that mimick the Excel interface
* Tab widgets at the bottom for selecting sheet tables
* Progress bar for showing status when loading an Excel file
* Modular API that can be easily extended
 

### Pre-requisite

The widget is dependent on the [xlrd](https://xlrd.readthedocs.io/en/latest/index.html) library for reading Excel data hence it must be installed prior. Installation instruction are available [here](https://xlrd.readthedocs.io/en/latest/installation.html).

### Usage

```buildoutcfg
from table_widget import ExcelWorkbookView

ewv = ExcelWorkbookView()
ewv.load_workbook('D:/test_data/sample_data.xlsx')

```

### License

You can redistribute it and/or modify it under the terms of the GNU General Public License version 3 (GPL v3) as published by the Free Software Foundation. The full GNU General Public License is available in LICENSE.txt or [here](https://www.gnu.org/licenses/gpl-3.0.en.html).
    

