# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [2.20.0-2](https://gitlab.com/anatec/wesave/welearn-back/compare/tpbp-pre.2.20.0-1...tpbp-pre.2.20.0-2) (2022-09-23)


### Features

* add allocation_detailed on portfolio serializer ([a97bf0c](https://gitlab.com/anatec/wesave/welearn-back/commit/a97bf0c7238186b32450dad3d96d013ddc9bbd3c)), closes [TT-1679](https://anatecteam.atlassian.net/browse/TT-1679)
* Added post-sync sanity check job (Primonial only) ([2065eb9](https://gitlab.com/anatec/wesave/welearn-back/commit/2065eb9a8008af073dcf60bb93b238b36ef691af))
* deep synchronization trigger for Primonial ([c7247b3](https://gitlab.com/anatec/wesave/welearn-back/commit/c7247b30aaa8ea90fbbd61a9e741d1ae1e0c5f1b))
* integrated sync subscription creation call ([f873e18](https://gitlab.com/anatec/wesave/welearn-back/commit/f873e18d7474dfc69b065bebaaed3a78ff20f31f))
* Investment enrichment on the fly strategy changed for Primonial ([5c04957](https://gitlab.com/anatec/wesave/welearn-back/commit/5c0495744ea42c48eba384305e8975c5e1645ed7))
* **JSON:API:** allow to filter attributes and relations for returned ressources ([77f88ef](https://gitlab.com/anatec/wesave/welearn-back/commit/77f88efecc44c2dc78666ee138fd2f9f8dd2f2d6)), closes [TT-1694](https://anatecteam.atlassian.net/browse/TT-1694)
* **JSON:API:** allow to limit the number of ressources returned (for collections) ([a82bc61](https://gitlab.com/anatec/wesave/welearn-back/commit/a82bc61cd1ca6ede001d61c1eedd7e0e99b4aebd)), closes [TT-1198](https://anatecteam.atlassian.net/browse/TT-1198)


### Bug Fixes

* **AgendaAPI:** prefix requests with LCL_AGENDA_PATH from env ([156386e](https://gitlab.com/anatec/wesave/welearn-back/commit/156386e7d47bdeffc88acb2e3d035004943fdbc1))
* **API Reco LCL:** ensure we use the selected pivot account (and not the default one) ([6d72331](https://gitlab.com/anatec/wesave/welearn-back/commit/6d72331fbc59f687d7658119987077fe9b14a2a6)), closes [TT-1697](https://anatecteam.atlassian.net/browse/TT-1697)
* **Hors Conseil:** Review rules linked to Hors Conseil in DMP ([1509ea7](https://gitlab.com/anatec/wesave/welearn-back/commit/1509ea7fdc4aee297a690e74391fee381fd38514)), closes [TT-1638](https://anatecteam.atlassian.net/browse/TT-1638)
* Primonial webhook moved account scope detection ([f7373c5](https://gitlab.com/anatec/wesave/welearn-back/commit/f7373c5c26181d5e83cb1d8efb1080cd4551b5bd))
* **Real Estate Credits:** Fix default loan_type not being taken into account for credits created via lcl ([3b9232c](https://gitlab.com/anatec/wesave/welearn-back/commit/3b9232ceee0db51e1d0f48ab1c0abfa7ee10948a))
* relax checks in config loading ([b6e8fd3](https://gitlab.com/anatec/wesave/welearn-back/commit/b6e8fd3648c608424dfecfec61b74ab3abf35f91))
* Report errors from Primonial general failure ([de6c51f](https://gitlab.com/anatec/wesave/welearn-back/commit/de6c51fc5e15d99a0ac5f27e519e6ce73926fe47))
* **weight rounding:** change precision from 4 to 10 ([6e48100](https://gitlab.com/anatec/wesave/welearn-back/commit/6e481008786063c5a5e20b0fe139c49934f9a583)), closes [TT-1698](https://anatecteam.atlassian.net/browse/TT-1698)
