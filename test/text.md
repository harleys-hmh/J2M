
1. "Setup Area" - see MEXNP-562
2. "Interaction Area"
    1. "Layout settings" contains:
        1. "Drag trays are" - radio buttons with labels:
            1. At the bottom
            2. On the right
        2. "Labels in drop areas are" - radio buttons with labels: On top, On the right, On bottom, On the left
    2. "Validation settings" panel:
        1. "Assign numbers to drag items and drop areas" radio group: Yes (default), No
    3. "Regions" contains:
        1. Image element
            1. "Add image" button which, if selected, presents with the “Edit Image” screen
            2. "Caption" rich text input - 160 Character guide
            3. "Credits" rich text input
            4. "Alt text" text input
        2. Preview element
            1. Displays background image {color:red}(# ??){color}
            2. Displays all available drop areas {color:red}(AC # ??){color} as pink rectangles which:
                1. {color:red}May display a label configured somewhere?{color}
                2. Can be transformed by dragging the element itself or individual vertices, or by rotating the element itself
        3. Drop areas
            1. "+ Add drop area" link
            2. Numeric list showing all available drop areas, and active drop area
            3. "Grid selector" contains:
                1. Delete button
                2. "Use cells to align drag items" - checkbox
                    1. If selected, displays:
                        1. Rows - numeric input
                        2. Columns - numeric input
                        3. Preview table showing Rows x Columns, displaying an asterix (\*) where cells contains 1+ drag item(s)
                    2. {color:red}Otherwise, if numbers are being assigned (AC#1.2.3), display:{color}
                        1. {color:red}"Optional total value" numeric input, supporting integers and decimal values to the thousandth (no min/max){color}
                3. "Available drag items" list previewing drag items from {color:red}(AC #??){color}
                    1. If cells are enabled (AC #??), author must select single cell in preview table to activate selection of drag items
                    2. Otherwise, list will be active
                    3. Once activated, any combination of drag items can be selected from the list to associate valid drag items for the active drop area
    4. "Drag tray settings" panel contains:
        1. "Content Type: - radio group, supporting:
            1. Text (default)
            2. Image
            3. Equation
        2. "Tray type" - radio group, supporting:
            1. Dispenser (default)
            2. Non-dispenser
    5. "Drag tray(s)"
        1. "Randomize items in this tray?" - toggle
        2. *Drag item" panel
            1. "Item content" will display different fields based on content type selected in {color:red}AC # (???){color}:
                1. Text - rich text input
                2. Image - Standard image inputs
                3. Equation- Standard equation inputs
            2. Number of items:
                1. "Number of items" input textbox - min 1 / max 20, placeholder text "Between 1 and 20"
                2. "Infinite" toggle switch
                    1. {color:red}Only available for "Dispenser" tray type - see {color:red}AC #?{color}
                    2. If enabled, will disabled/clear "Number of items"
            3. "Optional numeric value" - text input, placeholder "Enter integer value"
                1. Only available if "Assign numbers to drag items and drop areas" is set to "Yes" - see AC # ???
                2. To be used where the drag item is required to have a value - e.g. square = 100, line = 10, circle = 1
            4. "Item size in tray" - dropdown providing sizes Small, Medium, Large
            5. "Optional VO text" - VO input, placeholder "Enter VO text"
            6. {color:red}"Target drop areas:" listing all target areas added{color} - delete
            7. "+ Add drag item" button - min 1, max 10
                1. This will create another drag item {color:red}(see AC ??){color}
        3. "+Add drag tray" button, min 1, max 5
            1. This will create another drag tray {color:red}(see AC ??){color}
3. "Feedback & Hint Area"
