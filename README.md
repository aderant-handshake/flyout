# FlyOut
Markdown of Everything you need to know about Flyouts

| **Name**               | **Type**     | **Description**                                                                                                                                          |
|------------------------|--------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| **General Category**   |              |                                                                                                                                                          |
| Notes                  | Text         | General information about the control in context.                                                                                                        |
| Name                   | Text         | The name of the flyout                                                                                                                                   |
| Expanded               | CheckBox     | If checked, the flyout will initially display expanded                                                                                                   |
| **Behavior Category**  |              |                                                                                                                                                          |
| Condition              | Text         | Determines condition under which this widget renders                                                                                                     |
| OnChanged              | Text         | Script to execute when the state is finished changing                                                                                                    |
| OnChanging             | Text         | Script to execute before the state changes                                                                                                               |
| **Cosmetic Category**  |              |                                                                                                                                                          |
| Class                  | Text         | CSS classes to add to the container div of the Flyout                                                                                                    |
| Style                  | Text         | CSS style to add to the container div of the Flyout                                                                                                      |
| Direction              | Enumeration  | The direction from which the flyout appears.  From Left over Content  From Left-Fixed  From Right-Fixed  From Left  From Right over Content  From Right  |
| TabLabel               | Text         | Text/HTML to display in the flyout's tab  **Tip:** The tab is sized for an icon, not styled text.                                                        |
| Size                   | Float        | Optional width of flyout when expanded within its container. Enter a valid CSS value such as 200px or 10em.                                              |
| MinSize                | Float        | Optional minimum size when flyout is expanded. Enter a valid CSS value such as 200px or 10em.                                                            |
| MaxSize                | Float        | Optional maximum size when flyout is expanded. Enter a valid CSS value such as 200px or 10em.                                                            |
