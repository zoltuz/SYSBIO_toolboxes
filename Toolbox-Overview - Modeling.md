| Toolbox Name             | dmod           | d2d            | AMICI - Matlab    | AMICI - Python    | Copasi        |
|--------------------------|----------------|----------------|-------------------|-------------------|---------------|
|                          |                |                |                   |                   |               |
| **Model**                |                |                |                   |                   |               |
| *Possible model inputs*  | .xml/scripting | .xml           | .xml              | .xml              | .xml          |
| *Convert model*          | import_sbml    | arImportSBML() |                   |                   | -i            |
| *Standard model input*   | scripting      | .def           | .m .mat           | .m .mat           | user-supplied |
| *Function Loading model* | scripting      | arLoadModel()  | xlsread(); load() | xlsread(); load() | Model         |
|                          |                |                |                   |                   |               |
| **Data**                 |                |                |                   |                   |               |
| *Possible data inputs*   | .xls, .csv     | .xls, .csv     | .xlsx .mat        | h5, pandas        | tbd           |
| *Function Loading data*  | datalist()     | arLoadData()   | xlsread(); load() | xlsread(); load() | tbd           |
|                          |                |                |                   |                   |               |
| **Compile**              |                |                |                   |                   |               |
| *Compile model*          | odemodel()     | arCompile()    | amiwrap           | amiwrap           | no            |