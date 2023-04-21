JavaScript:function closeit(){ 
prodigydiv.remove()
} 
setTimeout("closeit", 3000);
function getallCurrencies() {
PIXI.game.prodigy.player.backpack.data.currency=[]
x = PIXI.game.state.states.Boot._gameData.currency
for (i in x) {
    PIXI.game.prodigy.player.backpack.data.currency[i] = {"ID": x[i].ID, "N": 9999999999}
}
}
function getallBuddies() {
PIXI.game.prodigy.player.backpack.data.follow=[]
x = PIXI.game.state.states.Boot._gameData.follow
for (i in x) {
    PIXI.game.prodigy.player.backpack.data.follow[i] = {"ID": x[i].ID, "N": 1}
}
}
function getallItems() {
PIXI.game.prodigy.player.backpack.data.item=[]
x = PIXI.game.state.states.Boot._gameData.item
for (i in x) {
    PIXI.game.prodigy.player.backpack.data.item[i] = {"ID": x[i].ID, "N": 9999999999}
}
}
function getallRelics() {
PIXI.game.prodigy.player.backpack.data.spellRelic=[]
x = PIXI.game.state.states.Boot._gameData.spellRelic
for (i in x) {
    PIXI.game.prodigy.player.backpack.data.spellRelic[i] = {"ID": x[i].ID, "N": 99999999999999}
}
}
function getallHats() {
PIXI.game.prodigy.player.backpack.data.hat=[]
x = PIXI.game.state.states.Boot._gameData.hat
for (i in x) {
    PIXI.game.prodigy.player.backpack.data.hat[i] = {"ID": x[i].ID, "N": 9999999999999999}
}
}
function getallOutfits() {
PIXI.game.prodigy.player.backpack.data.outfit=[]
x = PIXI.game.state.states.Boot._gameData.outfit
for (i in x) {
    PIXI.game.prodigy.player.backpack.data.outfit[i] = {"ID": x[i].ID, "N": 99999999999999}
}
}
function getallBoots() {
PIXI.game.prodigy.player.backpack.data.boots=[]
x = PIXI.game.state.states.Boot._gameData.boots
for (i in x) {
    PIXI.game.prodigy.player.backpack.data.boots[i] = {"ID": x[i].ID, "N": 99999999999999}
}
}
function getallWeapons() {
PIXI.game.prodigy.player.backpack.data.weapon=[]
x = PIXI.game.state.states.Boot._gameData.weapon
for (i in x) {
    PIXI.game.prodigy.player.backpack.data.weapon[i] = {"ID": x[i].ID, "N": 1}
}
}
function getallGems() {
PIXI.game.prodigy.player.backpack.data.key=[]
x = PIXI.game.state.states.Boot._gameData.k
