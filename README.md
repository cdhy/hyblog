#### 定制的AdminLTE 后台

- 基于Bootstrap 3.3.7 做了定制
- 修改了AdminLTE的文件结构
- 所有第三方插件均放在vendor下,包括AdminLTE
- 个人的css和js放在asset下


*正在逐步完善之中*

![面板1](https://github.com/cdhy/AdminLTE_HY/raw/master/images/dashboard1.png)

![布局-fixed](https://github.com/cdhy/AdminLTE_HY/raw/master/images/layout_fixed.png)

![图表-morris](https://github.com/cdhy/AdminLTE_HY/raw/master/images/charts_morris.png)

![UI_一般元素](https://github.com/cdhy/AdminLTE_HY/raw/master/images/ui_general.png)

![表单_一般](https://github.com/cdhy/AdminLTE_HY/raw/master/images/form_general.png)

![表格_简单类型](https://github.com/cdhy/AdminLTE_HY/raw/master/images/table_simple.png)

##### 项目结构
```
├── index.html
├── index2.html
├── chart_inline.html
├── invoice-print.html
├── sample_invoice.html
├── sample_lockscreen.html
├── sample_login.html
├── mailbox.html
├── ui_modals.html
├── chart_morris.html
├── sample_pace.html
├── sample_profile.html
├── read-mail.html
├── sample_register.html
├── table_simple.html
├── ui_sliders.html
├── ui_timeline.html
├── layout_top_nav.html
├── sample_404.html
├── sample_500.html
├── README.md
├── sample_blank.html
├── layout_boxed.html
├── ui_buttons.html
├── calendar.html
├── chart_chartjs.html
├── layout_collapsed_sidebar.html
├── compose.html
├── table_data.html
├── layout_fixed.html
├── chart_flot.html
├── form_advanced.html
├── form_editors.html
├── form_general.html
├── general.html
├── ui_icons.html
├── widgets.html 
├── images
│   ├── calendar.png
│   ├── charts_chartjs.png
│   ├── charts_flot.png
│   ├── charts_inline.png
│   ├── charts_morris.png
│   ├── dashboard1.png
│   ├── dashboard2.png
│   ├── example_404.png
│   ├── example_505.png
│   ├── example_blank.png
│   ├── example_invoice.png
│   ├── example_lockscreen.png
│   ├── example_login.png
│   ├── example_pace.png
│   ├── example_profile.png
│   ├── example_register.png
│   ├── form_advanced.png
│   ├── form_editor.png
│   ├── form_general.png
│   ├── layout_boxed.png
│   ├── layout_collapsed_sidebar.png
│   ├── layout_fixed.png
│   ├── mailbox.png
│   ├── nullfile
│   ├── table_data.png
│   ├── table_simple.png
│   ├── ui_buttons.png
│   ├── ui_general.png
│   ├── ui_icons.png
│   ├── ui_modals.png
│   ├── ui_sliders.png
│   ├── ui_timeline.png
│   └── widgets.png
├── vendor
│   ├── AdminLTE
│   │   ├── css
│   │   ├── img
│   │   └── js
│   ├── Flot
│   │   ├── API.md
│   │   ├── CONTRIBUTING.md
│   │   ├── FAQ.md
│   │   ├── LICENSE.txt
│   │   ├── Makefile
│   │   ├── NEWS.md
│   │   ├── PLUGINS.md
│   │   ├── README.md
│   │   ├── component.json
│   │   ├── examples
│   │   ├── excanvas.js
│   │   ├── excanvas.min.js
│   │   ├── flot.jquery.json
│   │   ├── jquery.colorhelpers.js
│   │   ├── jquery.flot.canvas.js
│   │   ├── jquery.flot.categories.js
│   │   ├── jquery.flot.crosshair.js
│   │   ├── jquery.flot.errorbars.js
│   │   ├── jquery.flot.fillbetween.js
│   │   ├── jquery.flot.image.js
│   │   ├── jquery.flot.js
│   │   ├── jquery.flot.navigate.js
│   │   ├── jquery.flot.pie.js
│   │   ├── jquery.flot.resize.js
│   │   ├── jquery.flot.selection.js
│   │   ├── jquery.flot.stack.js
│   │   ├── jquery.flot.symbol.js
│   │   ├── jquery.flot.threshold.js
│   │   ├── jquery.flot.time.js
│   │   ├── jquery.js
│   │   └── package.json
│   ├── Ionicons
│   │   ├── LICENSE
│   │   ├── bower.json
│   │   ├── cheatsheet.html
│   │   ├── component.json
│   │   ├── composer.json
│   │   ├── css
│   │   ├── fonts
│   │   ├── less
│   │   ├── png
│   │   ├── readme.md
│   │   ├── scss
│   │   └── src
│   ├── barcodegen
│   │   ├── README.txt
│   │   ├── VERSION_1D
│   │   ├── example
│   │   └── packages
│   ├── bootstrap
│   │   ├── css
│   │   ├── fonts
│   │   └── js
│   ├── bootstrap-colorpicker
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── bower.json
│   │   ├── dist
│   │   ├── docs
│   │   ├── package-lock.json
│   │   ├── serve.js
│   │   ├── spec
│   │   └── src
│   ├── bootstrap-datepicker
│   │   ├── CHANGELOG.md
│   │   ├── CODE_OF_CONDUCT.md
│   │   ├── CONTRIBUTING.md
│   │   ├── Gruntfile.js
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── bower.json
│   │   ├── build
│   │   ├── composer.json
│   │   ├── dist
│   │   ├── docs
│   │   ├── grunt
│   │   ├── js
│   │   ├── less
│   │   ├── package.json
│   │   ├── tests
│   │   └── yarn.lock
│   ├── bootstrap-daterangepicker
│   │   ├── README.md
│   │   ├── bower.json
│   │   ├── daterangepicker.css
│   │   ├── daterangepicker.js
│   │   ├── daterangepicker.scss
│   │   ├── demo.html
│   │   ├── drp.png
│   │   ├── example
│   │   ├── package.js
│   │   ├── package.json
│   │   └── website
│   ├── bootstrap-slider
│   │   ├── bootstrap-slider.js
│   │   └── slider.css
│   ├── bootstrap-wysihtml5
│   │   ├── bootstrap3-wysihtml5.all.js
│   │   ├── bootstrap3-wysihtml5.all.min.js
│   │   ├── bootstrap3-wysihtml5.css
│   │   └── bootstrap3-wysihtml5.min.css
│   ├── chart.js
│   │   ├── CONTRIBUTING.md
│   │   ├── Chart.js
│   │   ├── Chart.min.js
│   │   ├── LICENSE.md
│   │   ├── README.md
│   │   ├── bower.json
│   │   ├── docs
│   │   ├── gulpfile.js
│   │   ├── package.json
│   │   ├── samples
│   │   └── src
│   ├── ckeditor
│   │   ├── CHANGES.md
│   │   ├── LICENSE.md
│   │   ├── README.md
│   │   ├── adapters
│   │   ├── bower.json
│   │   ├── ckeditor.js
│   │   ├── composer.json
│   │   ├── config.js
│   │   ├── contents.css
│   │   ├── lang
│   │   ├── package.json
│   │   ├── plugins
│   │   ├── samples
│   │   ├── skins
│   │   └── styles.js
│   ├── datatables.net
│   │   ├── License.txt
│   │   ├── Readme.md
│   │   ├── bower.json
│   │   └── js
│   ├── datatables.net-bs
│   │   ├── License.txt
│   │   ├── Readme.md
│   │   ├── bower.json
│   │   ├── css
│   │   └── js
│   ├── fastclick
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── bower.json
│   │   └── lib
│   ├── font-awesome
│   │   ├── HELP-US-OUT.txt
│   │   ├── bower.json
│   │   ├── css
│   │   ├── fonts
│   │   ├── less
│   │   └── scss
│   ├── fullcalendar
│   │   ├── CHANGELOG.md
│   │   ├── CONTRIBUTING.md
│   │   ├── LICENSE.txt
│   │   ├── README.md
│   │   ├── bower.json
│   │   └── dist
│   ├── html5
│   │   ├── html5shiv.min.js
│   │   ├── modernizr-3.6.0.min.js
│   │   └── respond.min.js
│   ├── iCheck
│   │   ├── all.css
│   │   ├── flat
│   │   ├── futurico
│   │   ├── icheck.js
│   │   ├── icheck.min.js
│   │   ├── line
│   │   ├── minimal
│   │   ├── polaris
│   │   └── square
│   ├── input-mask
│   │   ├── jquery.inputmask.date.extensions.js
│   │   ├── jquery.inputmask.extensions.js
│   │   ├── jquery.inputmask.js
│   │   ├── jquery.inputmask.numeric.extensions.js
│   │   ├── jquery.inputmask.phone.extensions.js
│   │   ├── jquery.inputmask.regex.extensions.js
│   │   └── phone-codes
│   ├── jquery
│   │   ├── jquery-1.12.4.min.js
│   │   ├── jquery-3.1.1.min.js
│   │   └── jquery-3.3.1.min.js
│   ├── jquery-knob
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── bower.json
│   │   ├── dist
│   │   ├── excanvas.js
│   │   ├── index.html
│   │   ├── js
│   │   ├── knob.jquery.json
│   │   ├── package.json
│   │   └── secretplan.jpg
│   ├── jquery-slimscroll
│   │   ├── README.md
│   │   ├── bower.json
│   │   ├── examples
│   │   ├── jquery.slimscroll.js
│   │   ├── jquery.slimscroll.min.js
│   │   └── package.json
│   ├── jquery-sparkline
│   │   ├── Changelog.txt
│   │   ├── Makefile
│   │   ├── README.md
│   │   ├── bower.json
│   │   ├── dist
│   │   ├── minheader.txt
│   │   ├── sparkline.jquery.json
│   │   ├── src
│   │   └── version.txt
│   ├── jquery-ui
│   │   ├── AUTHORS.txt
│   │   ├── LICENSE.txt
│   │   ├── README.md
│   │   ├── bower.json
│   │   ├── component.json
│   │   ├── composer.json
│   │   ├── jquery-ui.js
│   │   ├── jquery-ui.min.js
│   │   ├── package.json
│   │   ├── themes
│   │   └── ui
│   ├── jvectormap
│   │   ├── jquery-jvectormap-1.2.2.css
│   │   ├── jquery-jvectormap-1.2.2.min.js
│   │   ├── jquery-jvectormap-usa-en.js
│   │   └── jquery-jvectormap-world-mill-en.js
│   ├── moment
│   │   ├── CHANGELOG.md
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── bower.json
│   │   ├── locale
│   │   ├── min
│   │   ├── moment.d.ts
│   │   ├── moment.js
│   │   ├── package-lock.json
│   │   ├── src
│   │   └── templates
│   ├── morris
│   │   ├── morris.css
│   │   └── morris.min.js
│   ├── pace
│   │   ├── pace.css
│   │   ├── pace.js
│   │   ├── pace.min.css
│   │   └── pace.min.js
│   ├── raphael
│   │   ├── bower.json
│   │   ├── dev
│   │   ├── license.txt
│   │   ├── raphael.js
│   │   ├── raphael.min.js
│   │   ├── raphael.no-deps.js
│   │   ├── raphael.no-deps.min.js
│   │   ├── webpack.config.js
│   │   └── yarn.lock
│   ├── select2
│   │   ├── CHANGELOG.md
│   │   ├── Gruntfile.js
│   │   ├── LICENSE.md
│   │   ├── README.md
│   │   ├── bower.json
│   │   ├── component.json
│   │   ├── composer.json
│   │   ├── dist
│   │   ├── docs
│   │   ├── package.json
│   │   ├── select2.jquery.json
│   │   ├── src
│   │   ├── tests
│   │   └── vendor
│   └── timepicker
│       ├── bootstrap-timepicker.css
│       ├── bootstrap-timepicker.js
│       ├── bootstrap-timepicker.min.css
│       └── bootstrap-timepicker.min.js
└── assets
      └── css
          └── app.css

   ```














