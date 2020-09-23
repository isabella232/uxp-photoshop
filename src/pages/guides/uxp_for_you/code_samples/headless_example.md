# Headless plugin

A "headless" plugin is one that has no user interface. When the user selects the plugin from Photoshop's Plugins menu, the plugin runs silently.

Why would you want to do this? If your plugin only does one thing, and has no options or user-entered parameters, you could create it without any UI. The only time you would need a UI would be if the plugin failed in some way, at which point you should display a dialog describing the failure.
