- 👋 Hi, I’m @pythontan2
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
pythontan2/pythontan2 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---> var dancer1;
var dancer3;
var dancer2;

whenSetup(function () {
  setBackgroundEffectWithPalette("color_cycle", "neon");
  setForegroundEffectExtended("hearts_colorful");
  makeNewDanceSpriteGroup(2, "ALIEN", "top");
  makeNewDanceSpriteGroup(2, "BEAR", "diamond");
  makeNewDanceSpriteGroup(2, "CAT", "grid");
  makeNewDanceSpriteGroup(2, "DOG", "row");
  makeNewDanceSpriteGroup(2, "PINEAPPLE", "circle");
  makeNewDanceSpriteGroup(6, "ROBOT", "circle");
  makeNewDanceSpriteGroup(2, "SHARK", "circle");
  makeNewDanceSpriteGroup(2, "SLOTH", "circle");
  makeNewDanceSpriteGroup(2, "UNICORN", "circle");
  doMoveLR('dancer1', MOVES.Clown, -1);
  changeMoveLR('dancer3', MOVES.ClapHigh, -1);
  stopMapping('dancer2', "scale", "bass");
  setPropEach(sprites, "scale", 50);
});
