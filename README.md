
# Floating Panel

I purposefully didn't write customization for this extnsion, because I recommend and encourage to write your own theme.

## While making your theme, here is a quick guide:

- #panel.floating is the panel selector the nonfloating panel when the extension is available makes it easier to write 2 seperate styles, when the extension is enabled and when it is not.

- #panel:floating is the panel selector for when it is floating.
- If you want your floating style to apply on overview: apply the same styleshet to #panel:floating and #panel:overview

---

You should delete stylesheet.css when you write your theme. Anything written there will overwrite any theme applied through gnome-tweaks.

### IMPORTANT!
Make sure the nonfloating and the floating styles both have the same allocated space, becuase it can and will crash your shell if they don't.
