<a name="0.0.16"></a>
## [0.0.16](https://github.com/Promact/md2/compare/0.0.15...v0.0.16) (2017-02-28)


### Breaking changes

* The `<md2-multiselect>` depricated component is removed in favor of `<md2-select multiple>`.


### Bug Fixes

* demo changes ([d5b6a10](https://github.com/Promact/md2/commit/d5b6a10))
* demo changes ([ee0d106](https://github.com/Promact/md2/commit/ee0d106))
* lint ([0a0152b](https://github.com/Promact/md2/commit/0a0152b))
* lint ([f6d480e](https://github.com/Promact/md2/commit/f6d480e))
* Fix (Chips) set function for adding new chip on input blur
* Fix (Color picker) set default color for invalid color
* Fix(chips) data binding issue of autocomplete in chips
* fix(datepicker) type change update popup issue
* fixed issues and update performance of all modules
* fix(toast) update performance and fixed issue of view-container-ref


### Features

* chore(tooltip) added support for html bindings


<a name="0.0.15"></a>
## [0.0.15](https://github.com/Promact/md2/compare/0.0.14...v0.0.15) (2017-02-20)


### Bug Fixes

* fix(colorpicker) added popup for open colorpicker,validate color
* chore(dialog) update animations
* fix(colorpicker) changes



<a name="0.0.14"></a>
## [0.0.14](https://github.com/Promact/md2/compare/0.0.13-2...v0.0.14) (2017-02-16)


### Breaking changes

* chore(datepicker, toast) update providers and depricated `forRoot()`


### Bug Fixes

* chore(dialog) update promise in open/close methods



<a name="0.0.13-2"></a>
## [0.0.13-2](https://github.com/Promact/md2/compare/0.0.13-1...v0.0.13-2) (2017-02-16)

### Breaking changes

* The `<md2-multiselect>` component is deprecated in favor of `<md2-select multiple>`. This component allows for multiple select options same as `ms2-multiselect` component does.
* The use of Module `forRoot` has been deprecated and will be removed in the next release. Instead, just simply import MaterialModule directly:

```ts
@NgModule({
imports: [
...
MaterialModule,
...
]
...
});
```


### Bug Fixes

* fixed datepicker positioning issues and make it in dialog
* fix(datepicker) ie issue #43, panel open inside view port #58
* fix(datepicker) formatting issue #69
* fix(datepicker) time format NAN issue #78
* fix(tabs) invalid active tab index
* 


### Features
* chore(tooltip) added scrolling and fixed performance issues
* chore(dialog) update animations
* chore(dialog) update performance and implementations
* update performance of all components
  

  <a name="0.0.13-1"></a>
## [0.0.13-1](https://github.com/Promact/md2/compare/0.0.13...v0.0.13-1) (2017-01-17)

### Breaking changes

* data-table: directives are now camelcase and renamed


### Bug Fixes

* fix(data-table) active page change event while page change after data updates
* fix(select) styling issue
* fix(datepicker) min/max date null or undefined to seta as default #37
* fix(datepicker) unable to clear issue #60
* fix(autocomplete) suggestion list not closing issue
* fix(autocomplete) require ngControl issue #57
* fix(data-table) pagination issues and performance


### Features

* chore(data-table) set rows per page select dropdown is material #59
* feat(date-table) sort by deeply
* feat(datepicker) responsive #32
* chore(datepicker) update html and styling structure
* feat(datepicker) handle years through keyboard
* feat(tooltip) multiple line support


<a name="0.0.13"></a>
## [0.0.13](https://github.com/Promact/md2/compare/0.0.12...v0.0.13) (2016-12-29)

### Breaking changes

* saperate bundlings and move its in bundles path

### Features

* feat(data-table) update pagination navigations
* feat(data-table) pagination change event


<a name="0.0.12"></a>
## [0.0.12](https://github.com/Promact/md2/compare/0.0.11...0.0.12) (2016-12-27)

### Bug Fixes

* fix(datepicker, select) styling issues
* fix(accordion) remove prefix sytles
* fix(autocomplete) lint free style
* fix(toast) lint free style
* fix(autocomplete) AoT issue #47


### Breaking changes

* The <md2-multiselect> element is deprecated in favor of <md2-select multiple>.



<a name="0.0.11"></a>
## [0.0.11](https://github.com/Promact/md2/compare/0.0.10-7...0.0.11) (2016-12-23)


### Bug Fixes

* AoT issue ([b99c18d](https://github.com/Promact/md2/commit/b99c18d))
* demo home issue ([6f7bbbe](https://github.com/Promact/md2/commit/6f7bbbe))
* first trap issue ([5961e2d](https://github.com/Promact/md2/commit/5961e2d))
* safari date issue [#20](https://github.com/Promact/md2/issues/20) ([c611574](https://github.com/Promact/md2/commit/c611574))


### Features

* api docs ([bca2bd7](https://github.com/Promact/md2/commit/bca2bd7))
* initial select multiple ([64d6765](https://github.com/Promact/md2/commit/64d6765))



<a name="0.0.10-7"></a>
## [0.0.10-7](https://github.com/Promact/md2/compare/0.0.10-6...0.0.10-7) (2016-12-16)


### Bug Fixes

* AoT issue ([b99c18d](https://github.com/Promact/md2/commit/b99c18d))
* first trap issue ([5961e2d](https://github.com/Promact/md2/commit/5961e2d))
* linting issues ([70a5c7d](https://github.com/Promact/md2/commit/70a5c7d))
* linting issues ([ecf9486](https://github.com/Promact/md2/commit/ecf9486))



<a name="0.0.10-6"></a>
## [0.0.10-6](https://github.com/Promact/md2/compare/v0.0.10-5...0.0.10-6) (2016-12-09)


### Bug Fixes

* updated performance and fixed bugs


<a name="0.0.10-5"></a>
## [0.0.10-5](https://github.com/Promact/md2/compare/v0.0.10-4...0.0.10-5) (2016-12-07)


### Features
* feat(toast) added toast config service for set toast duration globally


<a name="0.0.10-4"></a>
## [0.0.10-4](https://github.com/Promact/md2/compare/v0.0.10-3...0.0.10-4) (2016-12-07)


### Bug Fixes

* fix(menu) trigger to open menu


### Breaking Changes

* refactor(toast) open/toast api changes



<a name="0.0.10-3"></a>
## [0.0.10-3](https://github.com/Promact/md2/compare/v0.0.10-2...0.0.10-3) (2016-12-06)


### Bug Fixes

* fix: AoT issue
* chore(tooltip) position and display variables should be public


### Breaking Changes

* Reimplement Menu component and changed its APIs, refer [docs](https://github.com/Promact/md2/blob/master/src/lib/menu/README.md).


<a name="0.0.10-2"></a>
## [0.0.10-2](https://github.com/Promact/md2/compare/v0.0.10...0.0.10-2) (2016-11-29)


### Bug Fixes

* style linting issues. ([da1b927](https://github.com/Promact/md2/commit/da1b927))


### Bug Fixis

* fix(select) require validation issue
* fix(toast) move applicationRef -> viewContainerRef to overlay
* fix(tooltip) move applicationRef -> viewContainerRef to overlay


### Features
* feat(data-table) handle active page


### Breaking Changes

* Renamed `md2-active-page` to `activePage` and made it as two way binding property


<a name="0.0.10"></a>
## [0.0.10](https://github.com/Promact/md2/compare/v0.0.9...0.0.10) (2016-11-24)


### Bug Fixes

* style linting issues. ([da1b927](https://github.com/Promact/md2/commit/da1b927))


<a name="0.0.9"></a>
## [0.0.9](https://github.com/Promact/md2/compare/0.0.8...0.0.9) (2016-11-18)


### Bug Fixes

* fix(datatable) update arrya dynamic issue.
* fix(select) ngModal binding issue.



<a name="0.0.8"></a>
## [0.0.8](https://github.com/Promact/md2/compare/0.0.7...0.0.8) (2016-11-15)

### Bug Fixes

* fix(accordion) multiple boolean issue


<a name="0.0.7"></a>
## [0.0.7](https://github.com/Promact/md2/compare/0.0.6...0.0.7) (2016-11-11)


### Bug Fixes

* autocomplete pipe issue ([65a38e6](https://github.com/Promact/md2/commit/65a38e6))
* sort field design
* chips improvements

### Features

* dev-app server open on browser ([2f70f65](https://github.com/Promact/md2/commit/2f70f65))


<a name="0.0.6"></a>
## [0.0.6](https://github.com/promact/md2/compare/md2@0.0.5...md2@0.0.6) (2016-10-20)

### Bug Fixes
*	fix(data-tagle) position


<a name="0.0.5"></a>
## [0.0.5](https://github.com/promact/md2/compare/md2@0.0.4...md2@0.0.5) (2016-10-20)

### Features
* feat(autocomplete, datepicker, multiselect, select) readonly, required functionality.
* feat(select) option label
* feat(autocomplete) min-length
* chore(data-table) create data-table

### Bug Fixes
*	fix(autocomplete) readonly input
* fix(tags) key event issue
* fix(tags) highlight issue
* fix(autocomplete) update set value
* fix(toast) text wrap
* fix(tooltip) position
* fix(colorpicker) import service


<a name="0.0.4"></a>
## [0.0.4](https://github.com/promact/md2/compare/md2@0.0.3...md2@0.0.4) (2016-10-10)

### Features
* feat(datepicker) seconds format

### Bug Fixes
*	fix(autocomplete, datepicker, multiselect, select, tags) change event fire on module change.
* minor bug fixis


<a name="0.0.3"></a>
## [0.0.3](https://github.com/promact/md2/compare/md2@0.0.2...md2@0.0.3) (2016-10-07)

### Features
* feat(Datepicker): Add seconds to format
* feat(datepicker) year selection
* feat: BooleanFieldValue annotation
* Added Chips component

### Bug Fixes
* fix(autocomplete, datepicker, multiselect, select, tags) initial binding conflict
* minor bug fixis


<a name="0.0.2"></a>
## [0.0.2](https://github.com/promact/md2/compare/md2@0.0.1...md2@0.0.2) (2016-10-03)

### Features
* feat(datepicker) update key events

### Bug Fixes
* fix: disabled component issue
* fix(autocomplete) null event fire on every escape key
* fix(autocomplete) disable issue
* fix(tags) design issues.
* fix(select) update demo and update design
* fix(select) binding issue
* fix(select) binding issue and update key events.
* fix(datepicker, multiselect, select) IE11 focus issue
* update core module
* fix(dialog) header design
* fix(toast) cross browser animation
* fix(toast) layout discard after clear all toasts
* fix(datepicker) clock issue
* minor bug fixis


<a name="0.0.1"></a>
## 0.0.1 (2016-09-29)

### Features
* feat(datepicker) initial features

### Bug Fixes
* upgrade with Angular2@rc5 and @module implementations
* minor bug fixis
