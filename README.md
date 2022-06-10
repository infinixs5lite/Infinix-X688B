mv device/Infinix/Infinix-X688B device/infinix/x688b

mv device/infinix/x688b/twrp_Infinix-X688B.mk device/infinix/x688b/twrp_x688b.mk

sed -i s/Infinix-X688B/x688b/g device/infinix/x688b/*
