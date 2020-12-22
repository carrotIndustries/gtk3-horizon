# gtk3-horizon

Builds gtk3 on msys2 with a patch to work around a bug in Intel's Windows GPU drivers that causes Gtk to update window contents a frame too late if OpenGL is enabled.

https://github.com/carrotIndustries/gtk3-horizon/blob/master/mingw-w64-gtk3/0001-add-intel-win32-blit-workaround.patch is the actual patch.

See https://gitlab.gnome.org/GNOME/gtk/-/issues/3487

