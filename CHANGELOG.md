## v2.1.14
- fix(main): labelColor callback for CustomTooltips  
- chore: drop @babel/polyfill in favour of core-js@3 and regenerator-runtime, config fix
- fix(sliders): unexpected string issue, update ion-rangeslider, css
- fix(google-maps): load script once

##### dependencies update
- update: `@coreui/coreui-plugin-chartjs-custom-tooltips` to `^1.3.1`
- update: `@coreui/coreui-pro` to `^2.1.14`
- update: `bootstrap-daterangepicker` to `^3.0.5`
- update: `chart.js` to `^2.8.0`
- update: `codemirror` to `^5.47.0`
- update: `core-js` to `^3.1.4`
- update: `flag-icon-css` to `^3.3.0`
- update: `fullcalendar` to `~3.10.0`
- update: `ion-rangeslider` to `^2.3.0`
- update: `jquery` to `^3.4.1`
- update: `popper.js` to `^1.15.0`
- add: `regenerator-runtime` to `^0.13.2`
- update: `select2` to `^4.0.7`
- update: `@babel/cli` to `^7.4.4`
- update: `@babel/core` to `^7.4.5`
- update: `@babel/plugin-proposal-object-rest-spread` to `^7.4.4`
- add: `@babel/plugin-proposal-throw-expressions` to `^7.2.0`
- update: `@babel/preset-env` to `^7.4.5`
- update: `autoprefixer` to `^9.6.0`
- update: `browser-sync` to `^2.26.7`
- update: `babel-eslint` to `10.0.2`
- update: `clean-css-cli` to `^4.3.0`
- update: `js-beautify` to `^1.10.0`
- update: `nodemon` to `^1.19.1`
- update: `node-sass` to `^4.12.0`
- update: `eslint` to `^5.16.0`
- update: `eslint-plugin-compat` to `^3.1.1`
- update: `stylelint` to `^10.1.0`
- update: `stylelint-config-recommended-scss` to `^3.3.0`
- update: `stylelint-config-standard` to `^18.3.0`
- update: `stylelint-order` to `^3.0.0`
- update: `stylelint-scss` to `^3.8.0`

## v2.1.12
- chore: move .stylelintrc to ./ dir
- fix(basic-forms): add missing form-group
- fix(basic-forms.pug): add missing form-group
- refactor(fullcalendar): fc v3 layout style tweaks
- fix(select2-bootstrap.scss): form-validation-state missing icons
- refactor(advanced-forms): add SingleDatePicker example
- fix(advanced-forms): broken DateRangePicker layout (v3 css breaking changes)
- chore(build/vendors): removes hash tag from urls in css files
- update: `@coreui/coreui` to `^2.1.7`
- update: `bootstrap` to `^4.3.1`
- update: `codemirror` to `^5.44.0`
- update: `flag-icon-css` to `^3.3.0`
- update: `jquery` to `3.3.1`
- update: `popper.js` to `^1.14.7`
- update: `@babel/core` to `^7.3.4`
- update: `@babel/plugin-proposal-object-rest-spread` to `^7.3.4`
- update: `@babel/preset-env` to `^7.3.4`
- update: `autoprefixer` to `^9.4.9`
- update: `eslint` to `^5.14.1`
- update: `eslint-plugin-compat` to `^2.7.0`
- update: `js-beautify` to `^1.9.0`
- update: `nodemon` to `^1.18.10`
- update: `postcss-cli` to `^6.1.2`
- update: `stylelint` to `^9.10.1`
- update: `stylelint-scss` to `^3.5.4`
- lock: `ion-rangeslider` on `~2.2.0`

## v2.1.11
- feat(spinners): add bootstrap 4.2 spinners 
- feat(toasts): add bootstrap 4.2 toasts 
- update: `@coreui/coreui-pro` to `^2.1.6`
- update: `bootstrap` to `^4.2.1`
- update: `codemirror` to `5.42.2`
- update: `fullcalendar` to `^3.10.0`
- update: `ion-rangeslider` to `^2.3.0`
- update: `jquery-validation` to `^1.19.0`
- update: `popper.js` to `^1.14.6`
- update: `@babel/cli` to `^7.2.3`
- update: `@babel/core` to `^7.2.2`
- update: `@babel/plugin-proposal-object-rest-spread` to `^7.2.0`
- update: `@babel/preset-env` to `^7.2.3`
- update: `autoprefixer` to `^9.4.5`
- update: `chalk` to `^2.4.2`
- update: `eslint` to `^5.12.0`
- update: `js-beautify` to `^1.8.9`
- update: `node-sass` to `^4.11.0`
- update: `nodemon` to `^1.18.9`
- update: `postcss-cli` to `^6.1.1`
- update: `rimraf` to `^2.6.3`
- update: `stylelint-scss` to `^3.5.0`

## v2.1.9
- fix(collapse): add `mb-0` to accordion cards
- refactor(spinners): add `mb-0` to accordion cards
- refactor(forms): add `autocomplete`
- refactor(modals): add `mb-1` to buttons
- refactor(invoice): buttons add `d-print-none`
- refactor(spinners): tweaks & color for dark template
- update: `@coreui/coreui-pro` to `2.1.3`
- update: `chart.js` to `2.7.3`
- update: `codemirror` to `5.42.0`
- update: `flag-icon-css` to `3.2.1`
- update: `popper.js` to `1.14.5`
- update: `@babel/cli` to `7.1.5`
- update: `@babel/core` to `7.1.6`
- update: `@babel/preset-env` to `7.1.6`
- update: `autoprefixer` to `9.3.1`
- update: `browser-sync` to `2.26.3`
- update: `eslint` to `5.9.0`
- update: `eslint-plugin-compat` to `2.6.3`
- update: `js-beautify` to `1.8.8`
- update: `node-sass` to `4.10.0`
- update: `nodemon` to `1.18.7` (vulnerability removed)
- update: `npm-run-all` to `4.1.5` (vulnerability removed)
- update: `postcss-cli` to `6.0.1`
- update: `shelljs` to `0.8.3`
- update: `stylelint` to `9.9.0`
- update: `stylelint-order` to `2.0.0`
- update: `stylelint-scss` to `3.4.0`

## v2.1.8
- feat(switches): add disabled switch example
- fix(switches): missing ending semicolons
- fix(switches): add missing `<tr>`

## v2.1.7
- fix(pug): crossplatform use `path.sep` instead of `/` - thanks @vasilevich
- fix(cards): smooth collapse card - thanks @MartijnBastiaansen #378
- fix(header): migrate .divider to .dropdown-divider - thanks @vanam #406
- update: `@coreui/coreui-pro` to `2.0.21`
  - feat(sidebar): mobile clickout behaviour
  - fix(layout): sidebar on mobile issue [#23](https://github.com/coreui/coreui-angular/issues/23)
  - fix: sidebar, sidebar-minimizer `rtl` ie issues, tweaks
  - refactor(sidebar.js): ps minor cleanup

