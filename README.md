# Prerequisites
1) obviously a way to decrypt/rip the game
2) models exported with minmode's PMX noesis script
3) some brain power

# Usage

Set your Def texture in the Spheremap slot and your Sdw in the Toon slot

Now set your Materials as such

SubTex for anything that isn't a Face mesh and you can do Add or Multi for anything that is a face (leaving it disabled will make mmd ignore it entirely)

Finally use photoshop with nvidia tools to make any Cubemaps you might need (you can also use any external programs I haven't really tested much)

finally just duplicate Material.fx and just give it the proper names

if you want self shadow load HgShadow (I'm not using mmd's default shadowmap)

that should be it really just report any bugs/errors I've made
Errors related to normals cannot be repremanded at this time due to asset studio's lack of tagent export
also asset ripper does not work with this game

# Credits

HariganeP for HgShadow_ObjHeader
