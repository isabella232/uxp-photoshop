# Cross-application Example

Because UXP will be the standard way of supporting third-party developers across Creative Cloud applications, it's possible for a single plugin to support multiple applications.

This example demonstrates that, supporting both Photoshop and XD in a single package. This sample plugin itself does very little, since the DOMs of these two applications are very different.

> TBD: is require("uxp").host coming back?