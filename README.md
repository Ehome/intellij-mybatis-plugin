# This fork is compatible with latest IntelliJ Idea and it's free!

#Download

* You may directly install https://github.com/Chris-V/intellij-mybatis-plugin/blob/master/intellij-mybatis-plugin.jar
* Some fixes are from lizhanhui. You can see the repository here https://github.com/lizhanhui/intellij-mybatis-plugin/
* Original non-free version from seventh7 may be downloaded from http://plugins.jetbrains.com/plugin/7293

# Features

* Useful navigation between xml and mapper
* Support generating of statement, @Param annotation and mapper of xml
* Support some useful rename of mapper in xml
* Support correct result type for select statement in mapper xml
* Support correct unresolved attribute value of mapper xml
* Support refactor the name of mapper xml file when rename the mapper interface
* Support refactor for id based tag in mapper xml
* Support find usage of mapper interface and mapper xml element
* Highlight conflicting element of mapper xml as errors
* Auto register mapper as spring bean
* Support completion of jdbc type in mapper xml
* Support completion of referencing to select statement in mapper xml
* Support switching between java type and alias in mapper xml using intention keystroke
* Auto inject sql language in mapper xml
* Mapper parameter auto completion in xml while editing sql
    * \#{yourParameter}
    * @Param annotation based
    * Association is supported
* Support generating properties for elements of result map using intention keystroke
    * DataSource of intellij is required

#Generate

* Place your caret on your target
    * Declaration of mapper interface、method or parameter
* Shortcut: Option + Enter(Mac) | Alt + Enter(Windows)
* To generate statement quickly, you can provide some method generating models with "Idea Setting" -> "Mybatis"


# Contribute

1. You are very welcome to file a bug report in Github Issues tab. Pull request, for sure, is sincerely appreciated. 
