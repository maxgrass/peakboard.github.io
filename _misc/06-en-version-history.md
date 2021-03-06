---
layout: article
title: Version History
menu_title: Version History
description: Version History
lang: en
ref: misc-06
---

## 1.0.20.9 (30.04.2018)

* Added scroll- and zoomproperty to webview
* Added Lua Runtime property for Sreen Scale
* Fix for S7 custom variables

## 1.0.20.6 (24.04.2018)

* Reworked manually update functionality and added multiple manual update
* Timer scripts can be disabled now
* Fix for formatting Tablegrid with one line

## 1.0.19.7 (17.04.2018)

* OPC UA datasource allows now to call event Methods
* Peakbord IO Portal added possibility to pair Boxes with Peakboard IO Account
* Script performance updates
* Siemens S7:
  * Increased connection stability
  * Support for all prmitive datatype on all PLCs
  * implemented variable data validator for designer
  * can now organize variables in groups (structs)
* Timer scripts are global now
* Added control animations
* Added screen animations
* Improved package encryption
* Changed Bridge .NET Version from 4.5 to 4.6
* Fix for adding Controls over existing ones
* Fix for Webviews fatal error when missing c++ libs
* Fix for modified on start
* Fix for toggle switch control calling event on start
* Fix for validating new scripts
* Fix for resources stored in the screens
* Fix for casing of Lua functions
* Fix for adding a screen with empty name
* Fix for SAP datasource thread issues

## 1.0.18.0 (06.03.2018)

* Enhancements to the OPC UA data source
* New Icons
* Fix for bridge logging
* Fix for logging the runtime
* Fix for Box Properties
* Fix for the mail data source
* Fix for script validation

## 1.0.17.0 (16.02.2018)

* Fix for using templates and global scripts when opening a pbmx file
* Fix for select file dialog

## 1.0.16.0 (13.02.2018)

* Excel Datasource supports .xlsm files now
* Improved Error handling for Webtables and Webviews
* Fixes for copying controls with not existing fonts
* Fixes for Peakboard IO Tables

## 1.0.15.0 (09.02.2018)

* Improvements for Peakboard-Bridge
* Improvements for OPC UA Datasource
* Replaced Ribbon Bar Icons

## 1.0.14.4 (02.02.2018)

* Improvements for Peakboard-Bridge

## 1.0.13.4 (30.01.2018)

* Fix for Twitter/ Instagram with Images

## 1.0.13.0 (30.01.2018)

* OPC UA now supports method calls
* Peakboard-Bridge Stability Optimization

## 1.0.12.9 (22.01.2018)

* Internal changes without effects

## 1.0.12.0 (19.01.2018)

* Peakboard IO Pages published
* OPC UA supports certificates
* OPC UA Extensions
* Top and Left settings in the Property Panel
* Screen order changeable
* S7 now supports string variables
* Textticker Fixes and Extensions

## 1.0.11.6 (16.01.2018)

* OPC UA Datasource has been extended

## 1.0.10.0 (12.01.2018)

* First version of Peakboard IO Portals
* IMAP Mail Datasource wurde hinzugefügt
* Control icons have been reworked
* CSV data source can now retrieve data via bridge
* CSV data source can now use definable delimiters
* New text formatting for percentages
* Bridge stability improved
* Fixes for Lua Json Parsing
* Fix for table grid columns with special characters
* Fix for SAP Query queries without return values
* Fixes for S7 data source

## 1.0.9.0 (22.12.2017)

* New Control: Live Tiles
* First preview version for the OPC UA data source
* XML data can now be retrieved from the network
* Via Ctrl + L the current log can be displayed in the runtime.
* Fixes for Map Control, Image Control, Websnippet Control, Animated Gifs

## 1.0.8.17 (15.12.2017)

* Fix for changing fonts using a Lua script

## 1.0.8.7 (27.11.2017)

* Fix for local PDF files

## 1.0.8.4 (23.11.2017)

* Global Event Key Down has been added
* Global event key input has been added
* Fix changes in resources during runtime

## 1.0.8.0 (23.11.2017)

* Excel Chart Control
* Web resources have been added
* Bridge Resources were added
* Performance improvements for Lua scripts
* SAP message servers are now supported
* Lua Snippets were extended by Waiting Screen
* SAP over bridge is no longer supported

## 1.0.7.3 (08.11.2017)

* Two new templates have been added
* Fix for tablejoin Lua functions
* Fix for math. tonumber () and string. tostring () Lua functions

## 1.0.7.0 (06.11.2017)

* Fundamental changes for licensing
* Windows are opened depending on the screen size
* Tables Performance Improvements
* Table column changes can now be reset
* Fix for changing the password of a User Box by the Designer

## 1.0.6.5 (26.10.2017)

* Settings and variable dialogs have been reworked
* Fixes for gauges at the same maximum, minimum and current value
* Fixes for Intellisense

## 1.0.6.3 (19.10.2017)

* Insert category was added in the menu strip
* Peakboard-Bridge Dataqullen can be downloaded via Lua
* Insertion wizard for images
* Syntax editor has been reworked
* New code snippets have been added
* Fix for Max, Min and Sum Function

## 1.0.5.0 (06.10.2017)

* Pop-up notifications can be displayed
* Revision of the error display in the preview
* New templates have been added
* Lua objects and functions can now be called in lower case
* Script suggestions are now all lowercase
* Changes of Peakboard-Box IP addresses are updated automatically
* Fix for Excel with language-dependent decimal places
* Fixes for Script Validation and Script Editor

## 1.0.4.0 (29.09.2017)

* The Template Dialog has been divided into categories
* Queries in Excel data sources now offer the possibility to define ranges
* Excel files can now be created as a resource
* A waiting bar can now be displayed via Lua
* The script editor font has been changed
* Double-clicking a button now opens the script editor
* Data changes that cause changes in controls can now be disabled
* Additional templates have been added
* Dropbox API V. 1 Usage replaced by V. 2
* Fix for Global Lua functions
* Fix for the validator in Global Lua scripts

## 1.0.3.1 (22.09.2017)

* Script Editor dialog has been revised
* Version history was linked in the about dialog

## 1.0.3.0 (22.09.2017)

* The Lua Script Editor has been reworked
* Voice input was added (beta)
* Bridge data source error handling has been optimized
* Bridge data source now allows dynamic calls
* Some dialogs of data sources have been reworked
* Scripts in resource files can now be called directly from the script editor
* Fixed for feed data source
* Fixes for Excel data source
* Fix for bindings of lists

## 1.0.2.1 (14.09.2017)

* Fixed for Webpage table data source without authentication

## 1.0.2.0 (05.09.2017)

* Peakboard can now record voice commands via microphone
* Peakboard can now send data to an S7 controller
* New templates were added and the existing templates were revised
* Values of variables can now be stored on the box for the long term
* Global properties for boxes have been added
* Global properties for boards have been added
* Some GUI icons have been reworked
* Values of gauges can now be hidden
* Unnecessary settings in the gauges have been removed
* Numbers are now displayed independent of the language of the operating system
* Scripts can now be added directly to Resources using the right mouse button
* Variables are now called “Variables” and no longer “General Data”.
* Revision of some dialogs
* NET Core Runtime V1.0 has been increased to V1.1

## 1.0.1.2 (21.08.2017)

* Siemens S7 Data Source
* Send Mail function for LUA to send emails
* Drag and drop to move data sources and resources to folders
* Reactivation of the Screen IsEnabled Property
* Delete the Expand Collase folder functions
* ODBC databases can now be connected using the Peakboard-Bridge
* Fix for deleting empty folders
* Fix for SQLSever with empty column names
* Fix for creating new packages without admin rights

## 1.0.0.486 (31.07.2017)

* Fix for SQL data source with double values
* Fix so that a new control element can be seen immediately in front position
* Fix detection if something has changed in the visualization

## 1.0.0.483 (28.07.2017)

* Fixed table columns can only be designated with valid names.
* Fix for connection termination problems while publishing a Peakboard

## 1.0.0.482 (25.07.2017)

* Fix for selection field for fixed elements

## 1.0.0.481 (24.07.2017)

* Elements can now be fixed in the Peakboard Designer and thus made unmodifiable
* You can now create static tables that are initially empty.
* Authentication can now be passed for loading images from a URL
* PDF data can now be loaded from a URL
* Changes to the icons in the Control Layout area
* The selection field has been redesigned
* Screens can no longer be deactivated

## 1.0.0.475 (21.07.2017)

* New Interactive Controls (Date Picker, Time Picker)
* You can now call a pop-up dialog via Lua Script
* After a http push, the data source now fires a refresh event
* With RemoveAt you can remove an element from a defined index with Lua.
* Fixed size and position fixes when viewing windows in Peakboard-Designer
* Changes to the icons of some controls

## 1.0.0.469 (18.07.2017)

* New Interactive Controls (Flat Button, Repeat Button, Toggle Button, Toggle Switch, Check Box, Radio Button, Combo-Box, Slider)
* It is now possible to generate a Basic Authentication directly in the Lua Script
* Fixed for time data source with internal NTP servers
* Fix for CSV and JSon data source authentication
