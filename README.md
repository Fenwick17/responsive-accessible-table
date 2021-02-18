# Accessible and Responsive tables

Prototype application to create accessible and responsive tables.  
https://fenwick17.github.io/responsive-accessible-table/

## Use case
This is suitable for all tables where row is more important than the column. This should not be used when columns are more important 

## How it works
On mobile it collapses each table row into its own section. This will appear with the column heading on the left, and the value on the right. The behaviour through a screenreader will be exactly the same as that of the desktop version.
Each element has a role assigned to it, which allows the mobile version to keep table behaviour as it would be on desktop when using a screenreader.  
The table has been tested by various HMRC members, as well as someone who is visually impaired and uses a screenreader daily on a variety of devices.

## Steps to install
`npm install`  
`npm start`

| Screen reader | Tested  | 
| ------------- | :------:|
| VoiceOver     | &#10004;|
| JAWS          | &#10004;|
| NVDA          | &#10004;|
| TalkBack      | &#10004;|
