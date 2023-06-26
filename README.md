# SWC/GCNU Software Skills website

# To build locally
```bash
git clone https://github.com/neuroinformatics-unit/software-skills
cd software-skills
pip install -r docs/requirements.txt
rm -rf docs/build
sphinx-build docs/source docs/build
```

# To edit
## Adding a new course:
- Add a markdown file to the `docs/source/courses` directory (copying the structure of an existing course)
- Add the course to the `toctree` in `docs/source/courses/index.md`
- Add a card advertising the course in the `Upcoming courses` section of `docs/source/index.md`, using the syntax e.g.:
```
::::{grid} 1 2 2 3
:gutter: 3

:::{grid-item-card} {fa}`file-image;sd-text-primary` Date & Time
:link: courses/course-name
:link-type: doc

Course title
+++
Location <br>
Time
:::
```

## Once a course has run
- Move the card from `Upcoming courses` to `Previous courses`, and remove the time/location e.g.:
```
::::{grid} 1 2 2 3
:gutter: 3

:::{grid-item-card} {fa}`file-image;sd-text-primary` Date & Time
:link: courses/course-name
:link-type: doc

Course title
:::

```