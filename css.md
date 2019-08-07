# CSS: Cascading Style Sheets

### cascading

classes < ids < inline styles
'''

.class {
    display: none;
}

id{
    display: block;
}

<div style={{display:'flex'}} />
'''

### units
-'px': pixel units
-'rem': ratio against the font-size of the 'html' element
-'%': percentage units
-'vh'/'vw': viewheight/viewwidth. Useful for making sections with specific aspect ratios.

### layouts/flexbox
-'display:flex;'
-'flex-direction:'
    - 'row' (default)
    - 'column'
    - 'row-reverse'
    - 'column-reverse'
-'flex-shrink:0' will stop a flexbox child from shrinking
- 'align-items': aligns on the axis perpendicular to your layout
    - 'center'
    - 'flex-start'
    - 'flex-end'
    - 'space-between'
    - 'space-around'
- 'justify-content': aligns on the axis of the layout
