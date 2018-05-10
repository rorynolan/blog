+++
title = "filesstrings: An R Package for File and String Manipulation"
date = 2016-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Rory Nolan", "Sergi Padilla-Parra"]`.
authors = ["Rory Nolan", "Sergi Padilla-Parra"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In *The Journal of Open Source Software*."
publication_short = "In *JOSS*"

# Abstract and optional shortened version.
abstract = "`filesstrings` is an R package providing convenient functions for moving files, deleting directories, and a variety of string operations that facilitate manipulating file names and extracting information from strings. For example, R has no `file.move()`, just `file.copy()` and `file.rename()`, so the best way to move a file was to unintuitively rename it. `filesstrings` provides `file.move()`. The package's string operations mostly pertain to dealing with numbers contained within strings. It has a function `NiceFileNums()` for fixing file names such that their numbering is consistent with alphabetical order. For example, 'file10.txt' comes before 'file9.txt' in alphabetical order, so `NiceFileNums()` recognises this and renames them to 'file10.txt' and 'file09.txt' respectively. See documentation at  https://cran.r-project.org/package=filesstrings."

# Featured image thumbnail (optional)
# image_preview = "ijtiff_img_wide.png"

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["example-external-project"]

# Links (optional).
# url_pdf = ""
# url_preprint = "#"
# url_code = "#"
# url_dataset = "#"
# url_project = "#"
# url_slides = "#"
# url_video = "#"
# url_poster = "#"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Article", url = "https://doi.org/10.21105/joss.00260"}, {name = "CRAN", url = "https://cran.r-project.org/package=filesstrings"}, {name = "GitHub", url = "https://www.github.com/rorynolan/filesstrings"}]

# Does the content use math formatting?
math = false

# Does the content use source code highlighting?
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "filesstrings.png"
caption = "The `filesstrings` R package"

+++

`filesstrings` is available to download for free from [CRAN](https://cran.r-project.org/package=filesstrings) and [GitHub](https://www.github.com/rorynolan/filesstrings).