First_Custom_Widget
===============================

ie cutter

Installation
------------

To install use pip:

    $ pip install FirstWidget
    $ jupyter nbextension enable --py --sys-prefix FirstWidget


For a development installation (requires npm),

    $ git clone https://github.com//First_Custom_Widget.git
    $ cd First_Custom_Widget
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --sys-prefix FirstWidget
    $ jupyter nbextension enable --py --sys-prefix FirstWidget