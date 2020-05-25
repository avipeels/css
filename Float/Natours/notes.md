# Notes
1. Float elements ignore the height of the container. Use **Clear Fix** hack to make it work.
&::after {
        content: "";
        display: table;
        clear: both;
    }