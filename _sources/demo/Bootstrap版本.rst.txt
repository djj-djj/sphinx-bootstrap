Bootstrap版本
^^^^^^^^^^^^^^^^^^^^
Bootstrap版本通过bootstrap_version 主题选项来改变支持Bootstrap的版本。
sphinx_bootstrap_theme支持Bootstrap V2.3.2和Bootstrap V3.0.0。

配置版本
------------------
在conf.py中html_theme_options中加入以下代码::


    ＃选择Bootstrap版本。
    ＃值：“ 3”（默认）或“ 2”，此处选择Bootstrap V3.0.0即"3"
    'bootstrap_version':"3",





.. note:: 
        
        * Bootstrap 3放弃了对子菜单的支持，因此虽然受此主题支持，但它们不会显示在站点或页面菜单中。

        * 在内部，“ navbar.html”是用于Bootstrap v3的Sphinx模板，而“ navbar-2.html”是用于v2的模板。