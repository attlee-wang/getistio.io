# getistio.io
Website for GetIstio project. This supersedes previous project as we move from Gatsby to Hugo.

## Run Locally
1. Download and install [hugo](https://www.gethugo.io)
2. Fork this repo, clone it to your local machine 
3. Go to the cloned directory and run

```
hugo serve -D
```

## Adding Content
All contents are written in markdown. You can add main category by creating a folder in `/content` directory. The main index page for that new category is a file named `index_en.md` (for English page). To add child pages under that category, create additional folder in that category folder and add another `index.md` file.

As an example, to add a category named Installation, which contains 2 child pages named "Linux" and "MacOS", you need to add the following files and folders

- content
  - Installation
    - Linux
      - index_en.md
    - MacOS
      - index_en.md
    - index_en.md

Take a look at other file in the `/content` directory to see example of required frontmatter.

To add blog content, just add markdown file in `/content/blog` directory.