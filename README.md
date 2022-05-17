## Installation

To install rbenv-get, clone this repository into your rbenv plugins directory.

```shell
mkdir -p "$(rbenv root)"/plugins
git clone https://github.com/toy/rbenv-whatis.git "$(rbenv root)"/plugins/whatis
git clone https://github.com/toy/rbenv-get.git "$(rbenv root)"/plugins/get
```

### Example:

```shell
rbenv get 2.{0,1,2,3,4,5,6,7} 3
```
