# rendercv_example

A simple example of managing your [rendercv](https://github.com/rendercv/rendercv) resume in git

Uses a pre-commit hook to render the resume on commit so that the commited
resume renders and the render is up to date with what's commited.

# Installation

This assumes you've got [uv](https://github.com/astral-sh/uv?tab=readme-ov-file) up and running.

```sh
uv tool install pre-commit
uv tool install rendercv[full]
pre-commit install
```


# Usage

To render your resume, run:

```
rendercv render resume.yaml
```

