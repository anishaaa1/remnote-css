# What Does This CSS Snippet Do?
- Modifies existing headers (H1, H2, H3)
- Adds 3 more headers (H4, H5, H6)

# How to Use H4, H5, H6

- Create rems named H4, H5, and H6
- Copy these rems as tags (`Ctrl/Cmd` + `Shift` + `S`)
- Paste the tags to the rems you want to turn into H4/H5/H6-styled headers

# Screenshots

![image](https://user-images.githubusercontent.com/68901589/181594137-2af5414f-de47-4aa5-a93a-039189046cc4.png)

# Additional
## Hide H4, H5, H6 Tags for Less Clutter
To hide the rems created to use additional headers (H4, H5, H6), copy and paste this code into a separate code block.

```
[data-rem-container-tags~="h4"]:not([data-rem-container-tags~="show-tags"]) .hierarchy-editor__tag-bar {
	display: none;
}
[data-rem-container-tags~="h5"]:not([data-rem-container-tags~="show-tags"]) .hierarchy-editor__tag-bar {
   display: none;
}
[data-rem-container-tags~="h6"]:not([data-rem-container-tags~="show-tags"]) .hierarchy-editor__tag-bar {
   display: none;
}
```

### ❗️Warning
This makes it so that the only way you can remove the headers is by zooming into the rem tagged with H4/H5/H6 > Deleting the tag from here:

![untitled](https://user-images.githubusercontent.com/68901589/181208496-495606cd-2ffe-4804-b436-32f7c326eab9.png)
