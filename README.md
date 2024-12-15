# `Evgenii Frikin's blog`

*I want to thank @EllaKaye because she presented the website source code for
people who look for inspiration and a starting point for their own websites*

[My personal blog](https://blog.evgenii.us)

Built with [Quarto](https://quarto.org) and deployed to
[GitHub Pages](https://pages.github.com).

## `Usage`

```bash
git clone https://github.com/efrikin/efrikin.github.io.git
git lfs pull
```

### `Docker`

#### `Preview mode`

```bash
docker run
    --rm -ti \
    -u root \
    -p6411:6411 \
    -v $(pwd):/tmp \
    registry.gitlab.com/quarto-forge/docker/quarto \
        quarto preview --port 6411 --host 0.0.0.0
```

#### `Render`

```bash
docker run
    --rm -ti \
    -u root \
    -v $(pwd):/tmp \
    registry.gitlab.com/quarto-forge/docker/quarto \
        quarto render
```

## `License`

The code for the website is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/)
(CC BY-SA 4.0).

## `Please let me know!`

I love to hear when other people have found my code useful. If that's you,
please do [get in touch](https://blog.evgenii.us) to let me know and
share your site with me. It's also a great way for me to get to know other
people and their work, and I've come across great projects and ideas this way.
