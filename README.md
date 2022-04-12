
# Ansible Role:  `icingaweb2-themes`

Install Themes for icingaweb2.


[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/bodsch/ansible-icingaweb2-themes/CI)][ci]
[![GitHub issues](https://img.shields.io/github/issues/bodsch/ansible-icingaweb2-themes)][issues]
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/bodsch/ansible-icingaweb2-themes)][releases]

[ci]: https://github.com/bodsch/ansible-icingaweb2-themes/actions
[issues]: https://github.com/bodsch/ansible-icingaweb2-themes/issues?q=is%3Aopen+is%3Aissue
[releases]: https://github.com/bodsch/ansible-icingaweb2-themes/releases


## usage

```yaml
icingaweb_themes_install_dir: /usr/share/icingaweb2

icingaweb_themes:
  #
  unicorn:
    src: https://github.com/Mikesch-mp/icingaweb2-theme-unicorn.git
    version: v1.0.2
    images:
      - name: unicorn.png
        url: http://i.imgur.com/SCfMd.png
  #
  nordlicht:
    src: https://github.com/netzwerkgoettin/icingaweb2-theme-nordlicht.git
    version: master
    enabled: true
  #
  starwars-dark:
    src: https://github.com/marekbeckmann/IcingaWeb2-Star-Wars-Theme.git
    version: main
    images:
      - name: icon.png
        url: https://www.pngkit.com/png/full/75-757133_logo-star-wars-star-wars-logo-black-and.png
      - name: wallpaper.jpg
        url: https://wallpapercave.com/wp/wp7419777.jpg
```


---

## Author

- Bodo Schulz

## License

[Apache](LICENSE)

`FREE SOFTWARE, HELL YEAH!`
