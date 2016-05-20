transmart-metacore-plugin is a grails plugin to enable Metacore capabilities within TranSMART
This plugin is not built separately; it is built together with the other plugins when
transmartApp is built.

To enable the transmart-metacore-plugin, edit the Config.groovy file (found in ~/grails/tranmartConfig directory.)
An example of this file can be found in the root of the transmartApp directory of your project. You must use / edit this file
when installing the tranSMART application.

To enable the transmart-metacore-plugin:

1. Edit the ~/.grails/transmartConfig/Config.groovy file.
2. The Config.groovy file should contain a line near the end of the file which enables the metacore plugin: 
com.thomsonreuters.transmart.metacoreAnalyticsEnable=true
You can create this line if it does not exist, or set the value to true if does not already have that value.

Plugin parameters have three modes.  The lowest mode, the default, is called 'demo', followed by 'system', followed by 'user.'
Each mode can be overridden by the mode that is next higher up in the chain.

User parameters are specified in the MetaCore Plugin settings window.

Here are the parameters with their default values, where available:

com.thomsonreuters.transmart.metacoreURL='https://portal.genego.com'
com.thomsonreuters.transmart.metacoreDefaultLogin=''
com.thomsonreuters.transmart.metacoreDefaultPassword=''

com.thomsonreuters.transmart.demoEnrichmentURL='http://pathwaymaps.com:7080'
com.thomsonreuters.transmart.demoMapBaseURL='http://pathwaymaps.com/maps/'

