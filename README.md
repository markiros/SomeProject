Author: Markiros <markiros@gmail.com>

Установка проекта:
$ mkdir assets
$ mkdir protected/runtime
$ chmod -R 0777 assets
$ chmod -R 0777 protected/runtime

Установка модулей:
$ git submodule add https://github.com/yiiext/nested-set-behavior.git protected/extensions/nested-set-behavior
$ git submodule update --init