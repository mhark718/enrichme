# enrichme
a python script using the gzip library increases inventory items to 64
How to use it:
0. Set Up your inventory so that you generate a lot of what you want.
(I used it for books and diamonds) Save the game. You must exit the game to
get it to work.

1. Determine where your .minecraft directory is. ./.minecraft/saves/$1
2. copy the enrichme.py file to that location
3. Change to that directory 
4. execute the file python enrichme.py  from that location


Here is the script that takes the name from inside the Minecraft Application

cp enrichme.py ./.minecraft/saves/$1/enrichme.py
cd ~/.minecraft/saves/$1
python enrichme.py
cd

Notes:
This will give you 64 of everything, whether or not you are allowed to do it.
You will get 64 armour 64 Pickaxes.  64 dirt. 64 eggs. 64 blocks of diamond.
Once you have gotten one of an item, you can generate 64 of the items.

