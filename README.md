<!--
SPDX-FileCopyrightText: 2023 Dominik Wombacher <dominik@wombacher.cc>

SPDX-License-Identifier: MIT
-->

# Flappy Mascot ![Flappy Mascot](img/favicon.png)

A customizable Flappy Bird clone, with Tux as default Mascot.

Add [custom assets](custom/README.md) and flap around **any**thing you want.
Use the default, or play with whatever motive you like and have some fun!

Based on [Flappy Bird](https://github.com/IgorRozani/flappy-bird)
from [Igor Rozani](https://github.com/IgorRozani).

<!-- markdownlint-disable MD013 -->
[![REUSE status](https://api.reuse.software/badge/github.com/wombelix/flappy-mascot)](https://api.reuse.software/info/github.com/wombelix/flappy-mascot)
[![Mirror](https://github.com/wombelix/flappy-mascot/actions/workflows/mirror.yml/badge.svg)](https://github.com/wombelix/flappy-mascot/actions/workflows/mirror.yml)
<!-- markdownlint-enable MD013 -->

## Table of Contents

* [How to run](#how-to-run)
* [Source](#source)
* [Contribute](#contribute)
* [Assets](#assets)
* [License](#license)

## How to run

The game is build with [Phaser 3](https://phaser.io/) without additional dependencies.

Only a webserver that can serve static content is required to run and host the game.

For local test / demo purposes, you can use Python, for example by running
`python3 -m http.server`, afterwards the game is accessible via
<http://localhost:8000>.

If you prefer nodejs, install the http server `npm install http-server -g`
and run `http-server` in the same directory as the game source.

## Source

The primary location is:
[github.com/wombelix/flappy-mascot](https://github.com/wombelix/flappy-mascot)

Mirrors are available on
[Codeberg](https://codeberg.org/wombelix/flappy-mascot) and
[Gitlab](https://gitlab.com/wombelix/flappy-mascot).

## Contribute

Pick the platform you prefer and are most comfortable with.

Provide feedback, open an issue or create a pull / merge request.

## Assets

The assets used in this project come from [FlapPyBird](https://github.com/sourabhv/FlapPyBird)
created by [Sourabh Verma](https://github.com/sourabhv).

## License

Unless otherwise stated: `MIT`

All files contain license information either as a
`header comment` or a `corresponding .license` file.

[REUSE](https://reuse.software) from the [FSFE](https://fsfe.org/)
is implemented to verify license and copyright compliance.
