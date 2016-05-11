transmart-metacore-plugin is a grails plugin to enable Metacore capabilities within TranSMART
This plugin is not built separately; it is built together with the other plugins when
transmartApp is built.

To enable the transmart-metacore-plugin, edit the Config.groovy file (found in ~/grails/tranmartConfig directory.)
After a line that looks like this: 
// I002 – Insertion point 'end'

Add a line:
com.thomsonreuters.transmart.metacoreAnalyticsEnable=true

or change the value from 'false' to true.

