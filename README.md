# soapui-japanese-translation

## Status: Developing

## Install
1. Download SoapUI 5.2.1 from http://www.soapui.org/downloads/open-source.html
1. Install SoapUI
1. Download Pleiades 1.5.0 from https://osdn.jp/projects/mergedoc/releases/
1. Extract plugins directory into SoapUI home directory
1. Download pleiades-config.xml and bundle_ja.properties from here
1. Copy pleiades-config.xml into plugins/jp.sourceforge.mergedoc.pleiades/conf directory
1. Copy bundle_ja.properties into plugins/jp.sourceforge.mergedoc.pleiades/conf/additions directory
1. Open and edit soapui.bat. Adds next one line after run soapui comment.
set JAVA_OPTS=%JAVA_OPTS% -javaagent:../plugins/jp.sourceforge.mergedoc.pleiades/pleiades.jar

## License: GPLv3

