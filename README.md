# KIT Scripts

These are scripts I wrote to automate annoying student "work". Most of them fetch some html, extract PDF download links and download them in a specific folder structure in the current working directory.

Only for non-Ilias pages, since Ilias has a bulk download option which is... okay, kind of. I can also recommend the RSS functionality of Ilias.

# Dependencies

I write simple scripts in [fish](https://fishshell.com/), but if you replace all set-commands with bash variable assignment lines, it should be easy to port it to bash. Sorry, but bash is a pain if you know fish. The rest is default stuff:

    fish, curl, grep, sed, sort, wget
    
More complicated scripts may be written in python.

# Contribution

In the very unlikely case that you like/use my scripts and want to contribute, just use Github ;)

# TODO

- make "library script" with functions like `pdfs = fetchPDFsFromHTML(url, rexexList)` etc to avoid redundant code.
