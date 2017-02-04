openag\_fixtures
================

A collection of module files for flashing OpenAg sensor firmware.

Use with [openag_python](https://github.com/openaginitiative/openag_python) as
a stand-alone flash tool, or with [openag_brain](https://github.com/openaginitiative/openag_brain)
for runtime flashing.

Using with openag\_python
-------------------------

First, install `openag_python` (>0.1.5):

    pip install openag

Then:

    openag firmware flash -f openag_fixtures/default.json -f openag_fixtures/personal_food_computer_v2.json

