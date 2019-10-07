default : generate;

M4 = m4

generate :
	$(M4) index.html4 > ../index.html
	$(M4) -D M4_TITLE="Al Dente" game_pre.html4 aldente.html game_post.html4 > ../game/aldente/index.html
	$(M4) -D M4_TITLE="Cursed Coin" game_pre.html4 cursedcoin.html game_post.html4 > ../game/cursedcoin/index.html
	$(M4) -D M4_TITLE="Crown Dungeon" game_pre.html4 crowndungeon.html game_post.html4 > ../game/crowndungeon/index.html
