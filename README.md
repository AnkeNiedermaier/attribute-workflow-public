# PythonPart AttributeWorkflow

With this PythonPart it is possible to fullfill the complete workflow related to attribute and information managemenet. It mainly contains **3 individual steps** that can be executed more or less automatically:
- **define** attributes
- **assign** attributes to dedicated objects
- **create** a **mapping table** for the Ifc export

An **Excel file** with a predefined schema serves as bais for each of them that is also delivered and installed as essential component of the PythonPart.

## Installation

The PythonPart **AttributeWorkflow** can be installed directly from the PluginManager in ALLPLAN. 

Alternatively, the corresponding ***.allep** package can be downloaded from the [release page](https://github.com/AnkeNiedermaier/attribute-workflow-public/releases). ***.allep** files are ALLPLAN internal setups that can be installed via drag and drop into the program window.

At least the version 2026 is needed to install the PythonPart.

## Installed PythonPart Scripts

If the installation was successfull, the PythonPart **AttributeWorkfolw.pyp** can be found
in the ALLPLAN Library:
`Office` → `Library` → `ALLPLAN GmbH` → `AttributeWorkflow`

Besides the library, the PythonPart can also be found in the ActionBar in a newly created task area **AttributeTools** inside the task **Plug-ins**.

## Excel template

As the complete workflow covered with this PythonPart is based on Excel, a predefined file **Schema_AttributeWorkflow.xlsx** is also installed with the PythonPart. It is initially stored at the same place in the library (`Office` → `Library` → `ALLPLAN GmbH`) but can be moved afterward to any folder

> ⚠️IMPORTANT\
The schema and structure of the Ecxel file is fixed and predefined and should not be changed, otherwise the PythonPart will not run correctly! It is also recommended to work with a copy of the file and keep the original unchanged

## Preparation

All the definitions, parameters and information that are handed over to ALLPLAN in using the PythonPart have to be entered into the Excel file. Similar to the  worklflow steps, it contains the sheet
- Defintion
- Assignment
- Matrix
- Mapping

with all relevant rows, columns and cells

### Definition

to enter the parameters for the **creation of attributes** with a syntax similar to the one in ALLPLAN. Selection list values for the PullDown of ComboBox and ListBox attributes are entered in the column H and following

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src = "./docs/AttribDef_Allplan.png" width = 500/> <br><br>
<img src = "./docs/AttribDef_Table.png" width = 800/>


