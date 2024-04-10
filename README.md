# ebook-creator

## To Use

From command prompt in repos root directory:

* `> source util/functions`
* `> deps`
* `> build_book`

Content in markdown files should be added to the `contents` folder in alphabetical order of how they should appear in the ebook.

Images used in the content should be added to the `images` folder.

The cover for the ebook should be in a PDF in the root directory named `cover.pdf`.

Compiled ebook is saved in the `output` folder.

**Note:**  You will need to change image references in markdown files to the appropriate path given this folder structure (all references start with the root directory, so `../images/` is incorrect and `./images/` is correct). You will also need to change all links in markdown files that begin with `/blog/` to ones that begin with `https://earthly.dev/blog/`.
