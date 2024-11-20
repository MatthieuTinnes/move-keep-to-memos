# move-keep-to-memos
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
Move Google Keep data to [Memos](https://github.com/usememos/memos)

This script use [memos native API](https://memos.apidocumentation.com/reference)


## How to use
- Go to [Google Takeout](https://takeout.google.com/) and export Keep data
- Extract the ZIP
- Download the python script from [this repo](https://raw.githubusercontent.com/MatthieuTinnes/move-keep-to-memos/refs/heads/main/keep2memos.py)
- Put this script in the extracted archive, alongside Takeout folder
- Get a token for your memos instance, in parameters menu / my account
- Use this command with instance url and token : `python3 keep2memos.py --instance https://memos.myserver.com --token XXXX`
You can change the default folder with the --folder parameter


## What does this script import ? 

This script import text, associated ressources, label and original creation date.

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://jakebolam.com"><img src="https://avatars.githubusercontent.com/u/3534236?v=4?s=100" width="100px;" alt="Jake Bolam"/><br /><sub><b>Jake Bolam</b></sub></a><br /><a href="https://github.com/MatthieuTinnes/move-keep-to-memos/commits?author=jakebolam" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!