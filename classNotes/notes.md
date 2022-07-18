Display
    types of boxes
        block
        inline
        inline-block


block
    <>
    -tries to be as wide as possible
    -content before and after box appears on separate line
    -can have any other element as a child

inline
    <span></span>
    -allows other elements to sit to its left and right
    -cannot have a width and height set
    -doesn't respect top/bottom margin/padding

inline-block
    -allows other elements to sit to its left and right
    -respects width/height, and margin/padding (including top/bottom)

Float
    Useful for making a print design layout (Like in a newspaper!)
    left, right, none
    clear: life, right, none, both
    removed from normal flow of page, but thing 'float' around it (still in flow)

Clearfix
    if a floating element is 'floating' outside of it's container, this is a clearfix
        .clearfix::after {
        content: "";
        clear: both;
        display: table;
        }


