# JavaFX Project

## Overview
This project is a JavaFX application 

## RequirementsUser
- Java Development Kit (JDK) 11 or higher
- JavaFX SDK 11 or higher
- JavaFX User Library Jars





--module-path "D:\javafx-sdk-17.0.13\lib" --add-modules javafx.controls,javafx.fxml
--add-opens java.base/java.lang.reflect=ALL-UNNAMED
--add-opens java.base/java.lang=ALL-UNNAMED
--add-exports javafx.base/com.sun.javafx.runtime=ALL-UNNAMED
--add-exports javafx.controls/com.sun.javafx.scene.control=ALL-UNNAMED
--add-exports javafx.controls/com.sun.javafx.scene.control.behavior=ALL-UNNAMED

jtestcli -config "builtin://CWE 4.14" -publish -project.name "JavaFX" -project.sourcepath "C:\Users\Admin\git\JavaFX\src" -project.classpath "C:\Users\Admin\git\JavaFX\lib\*" -project.location "C:\Users\Admin\git\JavaFX" -project.encoding "UTF-8" -project.javahome "C:\Program Files\Java\jdk-17"

jtestcli -config "builtin://CWE 4.14" -data "C:\Users\Admin\git\JavaFX\example.data.json" -publish
