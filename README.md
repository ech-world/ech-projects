## Echelon Blockchain Project List

This is a public project list repo for [ech.world](https://ech.world/). If you want a project added here or if there's a need to modify existing information about [projects](/projects/), please submit a pull request. All accepted requests are pulled to [live site](https://ech.world/projects/) (see [pull logic](#pull-logic)).

### New entries

1. Fork [this repo](../../)
2. Place logo and other images that you want to use to [/\_images folder](/_images/) (please don't create any subfolders). Logo image file's aspect ratio must be 1:1, so please contain your logo in a square canvas (for example 200x200 or 500x500). PNG is preferred for images
3. Create a single markdown file for your project in [/projects folder](/projects/) (you can copy the [template](/projects/_template.md) or some [other project](/projects/) for starting point)
4. The front matter (stuff between --- triple hyphens) are for article properties. Please fill in title (project's name), logo filename without path, website URL, post excerpt (shortest possible description of the project) and input a single category (use some existing category from [other project entry](/projects/) or insert a new one)
5. Article content (stuff below latter ---) can be freely used to describe the project. Use images and links as much as you want. Site's typography is on the large side, so for headings please use a maximum size of Heading 3 (\#\#\# in markdown). See [live site](https://ech.world/projects/) for examples how articles are rendered. Format: project name (title) is shown as top header, post excerpt below that, project's logo and website as a row below that and article content below that
6. Submit pull request. I will check it and get back to you

### Pull logic
* Markdown file gets pulled to [live site](https://ech.world/projects/) once pull request is accepted
* Anything in [/\_images folder](/_images/) are included in the pull (push as many images as you need but no subfolders under [/\_images](/_images/), please)
* External images are not allowed (can't take any risks of someone modifying the external file)
* Any file or folder starting with an underscore (\_) is not included in the pull
* Any file or folder in [repo root](../../) is not included in the pull
