openag\_module_files
====================

A collection of module files for flashing OpenAg sensor firmware.

Use with [openag_python](https://github.com/openaginitiative/openag_python) as
a stand-alone flash tool, or with [openag_brain](https://github.com/openaginitiative/openag_brain)
for runtime flashing.

Using with openag\_python
-------------------------

First, install `openag_python` (>0.1.5):

    pip install openag

Then:

    openag firmware flash -f openag_module_files/default.json -f openag_module_files/personal_food_computer_v2.json

Note how multiple files can be specified. JSON structures are deeply merged
when multiple files are specified.

You can also install it as a standalone flash tool:

    git clone https://github.com/openaginitiative/openag_python.git
    cd openag_python
    pip install -e .[flash]
