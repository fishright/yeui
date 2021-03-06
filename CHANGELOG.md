## 1.7.0 (2018-01-14)
### Refactoring
* Singlely export a ``yeuiThemeConfig()`` method to config the theme
### Features
* Add checkbox component, support ``ngModel`` and ``change($event)``, used by group
* Add radio component, support ``ngModel`` and ``change($event)``, used by group
### Fix
* Fix missing char ``\`` in weui css

<hr />

## 1.6.16 (2018-01-09)
### Refactoring
* From now need to call ``config()`` method to regist a theme first
### Features
* Add theme ability, currently only support build-in weui theme
* Add ``weui.min.css`` as global style (only when weui theme configured)
### Fix
* Remove yarn-only script

<hr />

## 1.6.4 (2017-12-27)
### Fix
* Rightly destroy left dom when closed popups, only left one top level ``<div>`` container
* Add Native encapsulation to dialog component to avoid css conversion
### Refactoring
* Remove inner popup templates's html/css files (use inline-component instead)
* The package itself changes to use ``yarn`` from now
* Not publish ``.ts`` files any more, just ``.d.ts`` files correctly
### Features
* Use source map file(.js.map) instead of inline source map

<hr />

## 1.6.1 （2017-10-14）
### Fix
* dialog body display fixed

<hr />

## 1.6.0 （2017-10-14）
### Refactoring
* Refactor yup module under material2's code style
### Features
* use of popups more like materials's way
* use dialog() alert() load() toast() to call default templates of popups
### Breaking Changes
* audio module will no more update here and move to a new lib

<hr />

## 1.5.1 (2017-09-14)
### Fix
* update exports classes, remove unused some
### Refactoring
* refactor default popups(alert, dialog, toast, loader)
* seems a little more like material2 dialog creating
### Features
* now yup can use open() method to create a custom angular component and add it at the end of the body tag
### Breaking Changes
* now yup module no more need to add a \<yup\> tag, the popup dom will be added to the end of body tag

<hr />

## 1.4.2 (2017-09-13)
### Fix
* fix peerDependencies, remove package for Material2
* fix css class name in input/button component to avoid reflection
### Features
* add weui-style button component
### Breaking Changes
* not add Material2 component anymore, will soon build a new package

<hr />

## 1.4.0 (2017-09-04)
### Features
* add weui-style button component
### Breaking Changes
* not add Material2 component anymore, will soon build a new package