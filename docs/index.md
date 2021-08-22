# Welcome to imagetools

## Commands

* `imagetools blur [filename]` - Blur image
* `imagetools sharpen [filename]` - Sharpen image
* `imagetools smooth [filename]` - Smooth image
* `imagetools smooth+ [filename]` - Smooth image more

## Project layout

    imagetools.py    # The script.
    test_filter.py   # Test script.
    test_files/
        image.jpg  # Test image for use in GitHub Actions
        ...        # More files in future?
    .github/
        dependabot.yml
        workflows/
            codecov.yml
            codeql-analysis.yml
            compile-nuitka.yml
            main.yml
    poetry.lock      # Files for use with
    pyproject.toml   # the Poetry dependency manager
