<img src="https://cdn.rawgit.com/oh-my-fish/oh-my-fish/e4f1c2e0219a17e2c748b824004c8d0b38055c16/docs/logo.svg" align="left" width="144px" height="144px"/>

#### es theme
> A Powerline-style, Git-aware theme for [Oh My Fish][omf-link].

[![MIT License](https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square)](/LICENSE) [![Fish Shell Version](https://img.shields.io/badge/fish-v2.2.0-007EC7.svg?style=flat-square)](http://fishshell.com) [![Oh My Fish Framework](https://img.shields.io/badge/Oh%20My%20Fish-Framework-007EC7.svg?style=flat-square)](https://www.github.com/oh-my-fish/oh-my-fish)

<br/>

## Install
Make sure you have [Oh My Fish][omf-link] installed. Then just
```fish
$ omf install es
```

## Requirements
* Latest fish version with a builtin `string` function (above `2.2.0`, so please get the latest version from  `HEAD`)
* A font patched with additional glyphs: [Powerline](https://github.com/powerline/fonts), [Octicons](https://octicons.github.com/) and [Devicons](https://vorillaz.github.io/devicons/#/main) at their default codepoints (Powerline `E0A0-E0B3`, Octicons `F000-F0E8`, Devicons `E600-E6C5`). You can patch any font yourself with [FontForge](https://fontforge.github.io/en-US/)+[Font patcher](https://github.com/eugenesvk/nerd-fonts/blob/master/font-patcher)

## Features

* Git-aware theme with detailed __Git status__ in the left prompt (added, removed, modified, renamed, unstaged, stashed)
* __Node/Python/Ruby@gemset__ current version (local/global in a git folder, only local elsewhere) in the right prompt if respective virtual environment manager is installed (nvm, pyenv, rbenv/RVM)
* __Error status__ and __duration of last command__ in the right prompt
* Mac-notifications on completion of long commands (10+&nbsp;seconds by default) if terminal (iTerm and Terminal) is out of focus
* Limits path to __last two folders__ for better visibility, with `$HOME` directory abbreviated to `~`

## Screenshot

###__Git folder__
<p align="center">
<img src="https://github.com/oh-my-fish/theme-es/blob/master/Fish%20Prompt%20Git-es.png?raw=true">
</p>

###__Normal folder (no Git)__
<p align="center">
<img src="https://github.com/oh-my-fish/theme-es/blob/master/Fish%20Prompt%20NoGit-es.png?raw=true">
</p>

###__Normal read-only folder (no Git)__
<p align="left">
<img src="https://github.com/oh-my-fish/theme-es/blob/master/Fish%20Prompt%20NoGit%20Read-only-es.png?raw=true" width="280">
</p>

# License

[MIT][mit] © [eugenesvk][author]


[mit]:            http://opensource.org/licenses/MIT
[author]:         http://github.com/eugenesvk
[omf-link]:       https://www.github.com/oh-my-fish/oh-my-fish

[license-badge]:  https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square
