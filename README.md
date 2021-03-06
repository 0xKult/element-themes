# Element Themes

The themes listed here are all included by default in our [element-desktop](https://github.com/0xKult/element-desktop) repository.

## Developing

The default template is as follows:

```
"settingDefaults": {
        "custom_themes": [
            {
                "name": "Electric Blue",
                "is_dark": false,
                "fonts": {
                    "faces": [
                        {
                            "font-family": "Inter",
                            "src": [{"url": "/fonts/Inter.ttf", "format": "ttf"}]
                        }
                    ],
                    "general": "Inter, sans",
                    "monospace": "'Courier New'"
                },
                "colors": {
                    "accent-color": "#3596fc",
                    "primary-color": "#368bd6",
                    "warning-color": "#ff4b55",
                    "sidebar-color": "#27303a",
                    "roomlist-background-color": "#f3f8fd",
                    "roomlist-text-color": "#2e2f32",
                    "roomlist-text-secondary-color": "#61708b",
                    "roomlist-highlights-color": "#ffffff",
                    "roomlist-separator-color": "#e3e8f0",
                    "timeline-background-color": "#ffffff",
                    "timeline-text-color": "#2e2f32",
                    "timeline-text-secondary-color": "#61708b",
                    "timeline-highlights-color": "#f3f8fd",
                    "username-colors": ["#ff0000", ...]
                    "avatar-background-colors": ["#cc0000", ...]
                }
            }, {
                "name": "Deep Purple",
                "is_dark": true,
                "colors": {
                    "accent-color": "#6503b3",
                    "primary-color": "#368bd6",
                    "warning-color": "#b30356",
                    "sidebar-color": "#15171B",
                    "roomlist-background-color": "#22262E",
                    "roomlist-text-color": "#A1B2D1",
                    "roomlist-text-secondary-color": "#EDF3FF",
                    "roomlist-highlights-color": "#343A46",
                    "roomlist-separator-color": "#a1b2d1",
                    "timeline-background-color": "#181b21",
                    "timeline-text-color": "#EDF3FF",
                    "timeline-text-secondary-color": "#A1B2D1",
                    "timeline-highlights-color": "#22262E"
                }
            }
        ]
    }
```