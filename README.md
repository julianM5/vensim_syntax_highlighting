# Syntax Highlighting for Vensim using User-Defined Languagues (UDL) in Notepad++

## Introduction
When working with System Dynamics (SD) models, the equation for even a single variable can get very long and convoluted, making them difficult to grasp. This issue is neither new nor unique to SD: programmers face a similar challenge with code in every programming language. To help manage this, programming has long since come up with an approach aiding programmers in reading complex code: Syntax highlighting (a.k.a. code coloring or color coding).


This repository hosts the User-Defined Language (UDL) files for several [Vensim](https://vensim.com/) file extensions, designed to be used with [Notepad++](https://notepad-plus-plus.org/). The purpose of these UDL files is to enhance the editing experience of Vensim models by providing syntax highlighting within Notepad++, making it easier to read, write, and understand model files. Syntax highlighting helps differentiate elements such as comments, variables, and functions through color-coding, significantly improving the readability of code. For more details on UDL in Notepad++, visit the [Notepad++ UDL documentation](https://npp-user-manual.org/docs/user-defined-language-system/).

Note that the UDL-definitions in this repository are currently only available for the Microsoft Windows operating system.

## Supported File Types

The UDL files for Notepad++ in this repository support the following Vensim file extensions:

* ### Model files `.mdl` 
  Contain the equations, variables, and comments and other definitions that make up a Vensim model. Click [here](https://www.vensim.com/documentation/_mdl_model_files.html) for more information.

  Example:

  <img src="/assets/images/npp_udl_vensim_mdl_example.png" width="800">

  Click the link to download: [Vensim_mdl.udl.xml](/notepad-plus-plus_UDL/Vensim_mdl.udl.xml)

* ### Constant Input Files `.cin`
  Specify changes in constants or initial conditions for simulations, which e.g. can be used to simulate scenarios. Click [here](https://www.vensim.com/documentation/cin_files.html) for more information.
  
  Example:

  <img src="/assets/images/npp_udl_vensim_cin_example.png" width="800">

  Click the link to download: [Vensim_cin.udl.xml](/notepad-plus-plus_UDL/Vensim_cin.udl.xml)

* ### Graph Definition Files `.vgd`
  Create and modify custom graphs to display simulation results. Click [here](https://www.vensim.com/documentation/23980.html) for more information.
  
  Example:

  <img src="/assets/images/npp_udl_vensim_vgd_example.png" width="800">

  Click the link to download: [Vensim_vgd.udl.xml](/notepad-plus-plus_UDL/Vensim_vgd.udl.xml)

* ### Command Files `.cmd`
  Automate tasks within the Vensim environment, such as running simulations or exporting/importing data. Click [here](https://www.vensim.com/documentation/25670.html) for more information.

  Example:

  <img src="/assets/images/npp_udl_vensim_cmd_example.png" width="800">

  Click the link to download: [Vensim_cmd.udl.xml](/notepad-plus-plus_UDL/Vensim_cmd.udl.xml)

## Installation

To install the UDL files in Notepad++, follow these instructions:

1. Go to the [official Notepad++ website](https://notepad-plus-plus.org/downloads/) to download and install Notepad++. Skip this step if Notepad++ is already installed.
2. Download the desired UDL files from this repository. The files are in the `notepad-plus-plus_UDL` subfolder, named as `Vensim_***.udl.xml`. Alternatively, [download all](https://github.com/julianM5/vensim_syntax_highlighting/archive/main.zip).
3. Open the Run dialog (Win + R) or the address bar in Windows Explorer and type `%APPDATA%\Notepad++\userDefineLangs`, then press Enter. This will open the folder where Notepad++ stores user-defined languages.
4. Copy the downloaded UDL files (with `.xml` file extension) into this folder.
5. Restart Notepad++ if it was open during this process. The new syntax highlighting should now be available under the Language menu and will automatically get applied when opening the supported file types.

## Contributing

Contributions to improve the UDL files are welcome. To contribute:

1. Learn how to create and edit UDL files in Notepad++ by following the guide [here](https://npp-user-manual.org/docs/user-defined-language-system/).
2. Fork this repository.
3. Make your changes and commit them to your fork.
4. Submit a pull request with your improvements.

## License

This project is licensed under the GNU General Public License (GPL). See the [LICENSE](LICENSE) file in this repository for more details.

## Contact

For any inquiries or further assistance, please reach out to the project maintainers:

- julian.emmerich@m-five.de
