-| INSTALL JP FONT |-  
          
    sudo pacman -S noto-fonts-cjk
    sudo pacman -S noto-fonts
    sudo pacman -S noto-fonts-emoji

  
-| Hyprland add language |-  
cd  
ls -a  
cd .config  
ls -l  
cd hypr   
ls -l  
(sudo pacman -S nano)  
nano hyprland.conf   
FIND line 28 (kb_layout = us)  
write your language EXAMPLE  
kb_layout = us,jp,ru,th  
FIND line 31 kb_option =grp:alt_shift_toggle  
( ALT + SHIFT = CHANGE LANGUAGE )   
ctrl + x (in nano) + y + enter (maybe just ctrl + x and DONE)  
First my HyprlandV3 Bug when i do this cuz  
i write kb_option = grp:alt_shift_toggle and i use us main language it bug can't windowsKEY + q /  windowsKEY + e  
Second my HyprlandV3 not bug i don't know why  
i think it cuz i write kb_option =grp:alt_shift_toggle  
and i use us main language Japan when install Arch It not Bug  
BANZAI BANZAI !  
# [![](https://cdn.donmai.us/original/27/79/__musume_yuusha_no_kuse_ni_namaiki_da_and_1_more_drawn_by_osimder__2779660c66874791a52eb8387a4f8318.gif)](https://cdn.donmai.us/original/27/79/__musume_yuusha_no_kuse_ni_namaiki_da_and_1_more_drawn_by_osimder__2779660c66874791a52eb8387a4f8318.gif)
