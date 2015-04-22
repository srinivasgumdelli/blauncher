BLauncher is a simple android launcher, which supports query items from different sources such as application, contacts, settngs etc. You can also execute an action on item at given position.

sytax: `regex[/[position]action]`

For example: 'hello' means search hello from default sources, '1234' means search 1234 from contacts and call log, 'message/o' means open the first match of applications contains 'message' text, '/3c' means call the third phone number in the call log.

| **Sources** | **Actions** |
|:------------|:------------|
| All Sources | <ul><li>Copy to Clipboard (C)</li><li>Share (S)</li></ul>|
| All Applications (a) | <ul><li> Launch (o) </li> <li> Uninstall (u) </li><li> Application Info (i) </li> </ul>|
| Recent tasks (r) | <ul><li> Launch (o) </li> <li> Uninstall (u) </li><li> Application Info (i) </li> </ul> |
| Running apps (R) | <ul><li> Launch (o) </li> <li> Uninstall (u) </li><li> Application Info (i) </li> <li>Kill Application (k) </li> </ul> |
| Contacts (c) | <ul><li> Call (c) </li> <li> Send Message (m) </li><li> View Contact (v) </li></ul> |
| Call Log (l) | <ul><li> Call (c) </li> <li> Send Message (m) </li><li> Show or Create Contact (s) </li></ul> |
| Self (s) | <ul><li> Call (c) </li> <li> Send Message (m) </li><li> Show or Create Contact (s) </li> <li>Add to Calendar (e) </li><li>Search ColorDict (d)</li></ul> |
| SMS Inbox (m) | View Message (v) |
| Calendar (e) |<ul><li> View an Event (v)</li><li>Edit an Event (e)</li></ul> |

Apk: [Download](https://code.google.com/p/blauncher/source/browse/com.bob.blauncher-1.apk)

Screenshots: [See All](https://blauncher-screenshot.googlecode.com/git/)

![https://blauncher-screenshot.googlecode.com/git/init.png](https://blauncher-screenshot.googlecode.com/git/init.png)
![https://blauncher-screenshot.googlecode.com/git/sources.png](https://blauncher-screenshot.googlecode.com/git/sources.png)
![https://blauncher-screenshot.googlecode.com/git/switcher.png](https://blauncher-screenshot.googlecode.com/git/switcher.png)
![https://blauncher-screenshot.googlecode.com/git/settings.png](https://blauncher-screenshot.googlecode.com/git/settings.png)