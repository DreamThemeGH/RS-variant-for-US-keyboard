# RS-variant-for-US-keyboard
Kubuntu English keyboard layout with Serbian special letters right Alt variant.

Made and tested in Kubuntu 24.04. But I think it will work in Ubuntu too. At least the layout structure is the same there.
</br>
</br>It's just better to manually insert new variants and make backups of course. 
</br>Also, in case of failure, for example, if you do not register a new variant, 
the keyboard may partially not work after reboot. 
</br>You can use the on-screen keyboard and return, correct or restore the backup.

New versions of the layout and registration files can be replaced completely, or existing ones can be edited.</br>
You can change the default layout settings manually:
1. You need to add a new variant to the US layout file <b>/usr/share/X11/xkb/symbols/US</b>
![Add new variant of US layout](https://github.com/user-attachments/assets/2cf6604a-371e-46f1-acae-29c30f9994bc)
2. You need to register the new variant in <b>/usr/share/X11/xkb/rules/evdev.xml</b>
![Registration of a new keyboard layout variant](https://github.com/user-attachments/assets/eadb1a69-8d4c-4ea2-8527-87b6462230c4)
3. Reboot, and then choose a new variant of layout in the keyboard settengs "English with Serbian latin ralt(US, us_rs)"

Now you can enter special characters of the Serbian alphabet by holding down the right Alt key:
    </br> Z -> Ž
    </br> X -> Ć
    </br> C -> Č
    </br> N -> Nj
    </br> S -> Š
    </br> D -> Đ
    </br> F -> Dž
    </br> L -> Lj
