# Static File Hosting Repository

This repository contains static files for CodingNomads course, e.g. images and screenshots. Please adhere to the following structure:

```
course_name
└── imgs
    └── filename.png
```

e.g.:

```
javascript
└── imgs
    └── run_node.png
```

After uploading your static images to this repo, you will be able to link to them directly from your Markdown documents. Taking the example structure above, the correct Markdown link would look like so:

```markdown
![Your alt Text](https://github.com/CodingNomads/static/blob/main/javascript/imgs/run_node.png?raw=true)
```

Let's break up the different pieces of this URL:

- **Main URL**: This stays the same for all courses and files: `https://github.com/CodingNomads/static/blob/main/`
- **Course Name**: Your folder name, which should match the course name for consistency: `javascript/`
- **Image Folder**: Let's keep all the images in an "imgs" folder, in order to keep consistent structure and allow for potentially adding other static files down the line: `imgs/`
- **File Name**: The file name of the screenshot or image you want to link to, including its extension: `run_node.png`
- **Query Parameter**: In order to display the image instead of linking to its GitHub page, you need to add the query parameter: `?raw=true`

_Most_ parts of these URLs will be consistent throughout your course, and you can do a search+replace on your existing Markdown links, and [create a code snippet](https://codingnomads.github.io/creator-docs/02-markdown-course-creation/#auto-expand-text-snippets) for new ones.
