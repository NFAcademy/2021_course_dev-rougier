# Jupyter notebooks

The course content should be completely reflected in written materials provided as Jupyter notebooks. Worked out examples should be fully narrated, and no code cell should be left unexplained.

The notebooks are used as source to build learning sequences in the online courses, making use of our Open edX extension for viewing Jupyter notebooks.

## Instructions

1. Use a naming convention where each notebook filename is prepended with a number, reflecting the order of the lessons in the course.

2. List all notebooks in this README.

3. Add any Python package dependencies to the `requirements.txt` file in the parent directory.

4. Add a dockerfile if there are additional package dependencies (e.g. Jupyter extensions).

5. We recommend that all notebooks be shared under a dual license: BSD-3 or MIT license for code, and CC-BY license for text and media.

6. GitHub actions may be added to test that dependencies install and notebooks can execute successfully.

**Important**: Use plenty of headers to organize the notebooks, and split Markdown cells in short portions (no more than a scroll on a laptop display).

**Important**: For any images embedded in Markdown cells, we need you to use HTML tags, and provide at least a width: `<img src="../images/name.jpg" width="600" />`