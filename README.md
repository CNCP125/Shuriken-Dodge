# GBS: Shuriken dodge


### @diffs true


```assetjson
{
 "README.md": " ",
 "assets.json": "",
 "images.g.jres": "{\n    \"P8(e?*=JEU)diO20Zy9Q\": {\n        \"data\": \"hwQQABAAAAAAAAAAAAAAAAAAAAAAAAAAAA8PAAAAAAAA8AAAAPAPAAD//wDwDwAA8L/9D///D/D//xH/////////8f/////////b/////wD///H/////////Ef//////8L/9D///D/AA//8A8A8AAAAAAAAA8A8AAAAAAAAAAAAAAAAAAAAAAA==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"displayName\": \"ninjaImage\"\n    },\n    \"UuIp$[_Y^YD]5DP\": {\n        \"data\": \"hwQQABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAP8AAAAAAADwDwAAAAAAAL8PAAAAAA8Azw8AAAAA//+s/A8AAADwywrK+wAAAAD/rPz/DwAAAADPDwAPAAAAAL8PAAAAAAAA/wAAAAAAAPAPAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"displayName\": \"starImage\"\n    },\n    \"^[24S~cZqXfPcPYYw5H{\": {\n        \"data\": \"hwQQABAAAAAAAAAAAMDMzAC7u7u7vBHLsNHd3d3L3csbsczMzMsdy9vBZmbGyx3L28HWZsbL3cvbwWZmxssdy9vBZmbGyx3L28FmZsbL3cvbwWZmxssdy9vBZmbGyx3LG7HMzMzL3cuw0d3d3csdywC7u7u7vBHLAAAAAADAzMwAAAAAAAAAAA==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"displayName\": \"computerImage\"\n    },\n    \"*\": {\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"dataEncoding\": \"base64\",\n        \"namespace\": \"myImages\"\n    }\n}",
 "images.g.ts": "// Auto-generated code. Do not edit.\nnamespace myImages {\n\n    helpers._registerFactory(\"image\", function(name: string) {\n        switch(helpers.stringTrim(name)) {\n            case \"P8(e?*=JEU)diO20Zy9Q\":\n            case \"ninjaImage\":return img`\n. . . . . . f f f f f . . . . . \n. . . . . f f f f f f f . . . . \n. . f . f f f f f f f f f . . . \n. . . f f b f f f f f b f . . . \n. . f . f d 1 1 b 1 1 d f . . . \n. . . . f f 1 f d f 1 f f . . . \n. . . . . f f f f f f f . . . . \n. . . . . . f f f f f . . . . . \n. . . . . f f f f f f f . . . . \n. . . . f f f f f f f f f . . . \n. . . . f f f f f f f f f . . . \n. . . f . f f f f f f f . f . . \n. . . f . f f f f f f f . f . . \n. . . . . . f f f f f . . . . . \n. . . . . . f f . f f . . . . . \n. . . . . f f f . f f f . . . . \n`;\n            case \"UuIp$[_Y^YD]5DP\":\n            case \"starImage\":return img`\n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . f f . . . . . . . . . \n. . . . . . f f . . . . . . . . \n. . . . . . f b f . . . . . . . \n. . . . . . f c f . . . f . . . \n. . . . f f c a c f f f f . . . \n. . . f b c a . a c b f . . . . \n. . f f f f c a c f f . . . . . \n. . f . . . f c f . . . . . . . \n. . . . . . f b f . . . . . . . \n. . . . . . . f f . . . . . . . \n. . . . . . . . f f . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n`;\n            case \"^[24S~cZqXfPcPYYw5H{\":\n            case \"computerImage\":return img`\n. . . b b b b b b b b b . . . . \n. . b 1 d d d d d d d 1 b . . . \n. b 1 1 1 1 1 1 1 1 1 1 1 b . . \n. b d b c c c c c c c b d b . . \n. b d c 6 6 6 6 6 6 6 c d b . . \n. b d c 6 d 6 6 6 6 6 c d b . . \n. b d c 6 6 6 6 6 6 6 c d b . . \n. b d c 6 6 6 6 6 6 6 c d b . . \n. b d c 6 6 6 6 6 6 6 c d b . . \n. b d c c c c c c c c c d b . . \n. c b b b b b b b b b b b c . . \nc b c c c c c c c c c c c b c . \nc 1 d d d d d d d d d d d 1 c . \nc 1 d 1 1 d 1 1 d 1 1 d 1 1 c . \nc b b b b b b b b b b b b b c . \nc c c c c c c c c c c c c c c . \n`;\n        }\n        return null;\n    })\n\n    helpers._registerFactory(\"animation\", function(name: string) {\n        switch(helpers.stringTrim(name)) {\n\n        }\n        return null;\n    })\n\n}\n// Auto-generated code. Do not edit.\n",
 "main.blocks": "<xml xmlns=\"https://developers.google.com/blockly/xml\"><variables><variable id=\"b6(FKDNSv|XHIU9rX^S[\">mySprite</variable><variable id=\"+m0`]Jr3m=nq(,[*b7#D\">projectile</variable><variable id=\"^p$Wesje^o5@45eZW(:u\">mySprite2</variable><variable type=\"KIND_SpriteKind\" id=\"RB%gi}=j7Y/~u9}TE][J\">Player</variable><variable type=\"KIND_SpriteKind\" id=\"Inz9Tko8W)U.sIpB).sH\">Projectile</variable><variable type=\"KIND_SpriteKind\" id=\"m3=`$_TN!ifcm=.OG`}L\">Food</variable><variable type=\"KIND_SpriteKind\" id=\"KDvD:Tt3k7tX)_q|(rr^\">Enemy</variable><variable type=\"KIND_SpriteKind\" id=\"lsS24-|i*O*y%4d,vTP.\">Computer</variable></variables><block type=\"pxt-on-start\" x=\"0\" y=\"0\"><statement name=\"HANDLER\"><block type=\"gamesetbackgroundcolor\"><value name=\"color\"><shadow type=\"colorindexpicker\"><field name=\"index\">4</field></shadow></value><next><block type=\"gameSplash\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" _expanded=\"1\" _input_init=\"true\"></mutation><value name=\"title\"><shadow type=\"text\"><field name=\"TEXT\">Save the computers!</field></shadow></value><value name=\"subtitle\"><shadow type=\"text\"><field name=\"TEXT\">Avoid the ninja stars!</field></shadow></value><next><block type=\"variables_set\"><field name=\"VAR\" id=\"b6(FKDNSv|XHIU9rX^S[\">mySprite</field><value name=\"VALUE\"><shadow xmlns=\"http://www.w3.org/1999/xhtml\" type=\"math_number\"><field name=\"NUM\">0</field></shadow><block type=\"spritescreate\"><value name=\"img\"><shadow type=\"screen_image_picker\"><field name=\"img\">assets.image`ninjaImage`</field><data>{\"commentRefs\":[],\"fieldData\":{\"img\":\"P8(e?*=JEU)diO20Zy9Q\"}}</data></shadow></value><value name=\"kind\"><shadow type=\"spritekind\"><field name=\"MEMBER\">Player</field></shadow></value></block></value><next><block type=\"game_control_sprite\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" _expanded=\"0\" _input_init=\"true\"></mutation><value name=\"sprite\"><block type=\"variables_get\"><field name=\"VAR\" id=\"b6(FKDNSv|XHIU9rX^S[\">mySprite</field></block></value><value name=\"vx\"><shadow type=\"spriteSpeedPicker\"><field name=\"speed\">100</field></shadow></value><value name=\"vy\"><shadow type=\"spriteSpeedPicker\"><field name=\"speed\">100</field></shadow></value><next><block type=\"spritesetsetstayinscreen\"><value name=\"sprite\"><block type=\"variables_get\"><field name=\"VAR\" id=\"b6(FKDNSv|XHIU9rX^S[\">mySprite</field></block></value><value name=\"on\"><shadow type=\"toggleOnOff\"><field name=\"on\">true</field></shadow></value><next><block type=\"hudsetScore\"><value name=\"value\"><shadow type=\"math_number\"><field name=\"NUM\">0</field></shadow></value><next><block type=\"hudSetLife\"><value name=\"value\"><shadow type=\"math_number\"><field name=\"NUM\">3</field></shadow></value></block></next></block></next></block></next></block></next></block></next></block></next></block></statement></block><block type=\"gameinterval\" x=\"890\" y=\"30\"><value name=\"period\"><shadow type=\"timePicker\"><field name=\"ms\">1000</field></shadow></value><statement name=\"HANDLER\"><block type=\"variables_set\"><field name=\"VAR\" id=\"+m0`]Jr3m=nq(,[*b7#D\">projectile</field><value name=\"VALUE\"><shadow xmlns=\"http://www.w3.org/1999/xhtml\" type=\"math_number\"><field name=\"NUM\">0</field></shadow><block type=\"spritescreateprojectilefromside\"><value name=\"img\"><shadow type=\"screen_image_picker\"><field name=\"img\">assets.image`starImage`</field><data>{\"commentRefs\":[],\"fieldData\":{\"img\":\"EC|D.UuIp$[_Y^YD]5DP\"}}</data></shadow></value><value name=\"vx\"><shadow type=\"spriteSpeedPicker\"><field name=\"speed\">50</field></shadow><block type=\"device_random\"><value name=\"min\"><shadow type=\"math_number\"><field name=\"NUM\">-50</field></shadow></value><value name=\"limit\"><shadow type=\"math_number\"><field name=\"NUM\">50</field></shadow></value></block></value><value name=\"vy\"><shadow type=\"spriteSpeedPicker\"><field name=\"speed\">0</field></shadow><block type=\"device_random\"><value name=\"min\"><shadow type=\"math_number\"><field name=\"NUM\">-50</field></shadow></value><value name=\"limit\"><shadow type=\"math_number\"><field name=\"NUM\">50</field></shadow></value></block></value></block></value></block></statement></block><block type=\"gameinterval\" x=\"890\" y=\"210\"><value name=\"period\"><shadow type=\"timePicker\"><field name=\"ms\">2000</field></shadow></value><statement name=\"HANDLER\"><block type=\"variables_set\"><field name=\"VAR\" id=\"^p$Wesje^o5@45eZW(:u\">mySprite2</field><value name=\"VALUE\"><shadow xmlns=\"http://www.w3.org/1999/xhtml\" type=\"math_number\"><field name=\"NUM\">0</field></shadow><block type=\"spritescreate\"><value name=\"img\"><shadow type=\"screen_image_picker\"><field name=\"img\">assets.image`computerImage`</field><data>{\"commentRefs\":[],\"fieldData\":{\"img\":\"^[24S~cZqXfPcPYYw5H{\"}}</data></shadow></value><value name=\"kind\"><shadow type=\"spritekind\"><field name=\"MEMBER\">Computer</field></shadow></value></block></value><next><block type=\"spritesetpos\"><value name=\"sprite\"><block type=\"variables_get\"><field name=\"VAR\" id=\"^p$Wesje^o5@45eZW(:u\">mySprite2</field></block></value><value name=\"x\"><shadow type=\"positionPicker\"><field name=\"index\">0</field></shadow><block type=\"device_random\"><value name=\"min\"><shadow type=\"math_number\"><field name=\"NUM\">10</field></shadow></value><value name=\"limit\"><shadow type=\"math_number\"><field name=\"NUM\">150</field></shadow></value></block></value><value name=\"y\"><shadow type=\"positionPicker\"><field name=\"index\">0</field></shadow><block type=\"device_random\"><value name=\"min\"><shadow type=\"math_number\"><field name=\"NUM\">10</field></shadow></value><value name=\"limit\"><shadow type=\"math_number\"><field name=\"NUM\">110</field></shadow></value></block></value></block></next></block></statement></block><block type=\"spritesoverlap\" x=\"881\" y=\"479\"><value name=\"HANDLER_DRAG_PARAM_sprite\"><shadow type=\"argument_reporter_custom\"><mutation typename=\"Sprite\"></mutation><field name=\"VALUE\">sprite</field></shadow></value><value name=\"kind\"><shadow type=\"spritekind\"><field name=\"MEMBER\">Player</field></shadow></value><value name=\"HANDLER_DRAG_PARAM_otherSprite\"><shadow type=\"argument_reporter_custom\"><mutation typename=\"Sprite\"></mutation><field name=\"VALUE\">otherSprite</field></shadow></value><value name=\"otherKind\"><shadow type=\"spritekind\"><field name=\"MEMBER\">Projectile</field></shadow></value><statement name=\"HANDLER\"><block type=\"spritedestroy\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" _expanded=\"0\" _input_init=\"true\"></mutation><field name=\"effect\">effects.spray</field><value name=\"sprite\"><block type=\"argument_reporter_custom\"><mutation typename=\"Sprite\"></mutation><field name=\"VALUE\">otherSprite</field></block></value><value name=\"duration\"><shadow type=\"timePicker\"><field name=\"ms\">500</field></shadow></value><next><block type=\"mixer_play_sound\"><field name=\"sound\">music.knock</field><next><block type=\"startEffectOnSprite\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" _expanded=\"1\" _input_init=\"true\"></mutation><field name=\"effect\">effects.coolRadial</field><value name=\"sprite\"><block type=\"argument_reporter_custom\"><mutation typename=\"Sprite\"></mutation><field name=\"VALUE\">sprite</field></block></value><value name=\"duration\"><shadow type=\"timePicker\"><field name=\"ms\">1000</field></shadow></value><next><block type=\"hudChangeLifeBy\"><value name=\"value\"><shadow type=\"math_number\"><field name=\"NUM\">-1</field></shadow></value></block></next></block></next></block></next></block></statement></block><block type=\"spritesoverlap\" x=\"1635\" y=\"479\"><value name=\"HANDLER_DRAG_PARAM_sprite\"><shadow type=\"argument_reporter_custom\"><mutation typename=\"Sprite\"></mutation><field name=\"VALUE\">sprite</field></shadow></value><value name=\"kind\"><shadow type=\"spritekind\"><field name=\"MEMBER\">Player</field></shadow></value><value name=\"HANDLER_DRAG_PARAM_otherSprite\"><shadow type=\"argument_reporter_custom\"><mutation typename=\"Sprite\"></mutation><field name=\"VALUE\">otherSprite</field></shadow></value><value name=\"otherKind\"><shadow type=\"spritekind\"><field name=\"MEMBER\">Computer</field></shadow></value><statement name=\"HANDLER\"><block type=\"spritedestroy\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" _expanded=\"0\" _input_init=\"true\"></mutation><field name=\"effect\">effects.spray</field><value name=\"sprite\"><block type=\"argument_reporter_custom\"><mutation typename=\"Sprite\"></mutation><field name=\"VALUE\">otherSprite</field></block></value><value name=\"duration\"><shadow type=\"timePicker\"><field name=\"ms\">500</field></shadow></value><next><block type=\"mixer_play_sound\"><field name=\"sound\">music.baDing</field><next><block type=\"hudChangeScoreBy\"><value name=\"value\"><shadow type=\"math_number\"><field name=\"NUM\">1</field></shadow></value><next><block type=\"controls_if\"><value name=\"IF0\"><shadow type=\"logic_boolean\"><field name=\"BOOL\">TRUE</field></shadow><block type=\"logic_compare\"><field name=\"OP\">EQ</field><value name=\"A\"><shadow type=\"math_number\"><field name=\"NUM\">0</field></shadow><block type=\"hudScore\"></block></value><value name=\"B\"><shadow type=\"math_number\"><field name=\"NUM\">10</field></shadow></value></block></value><statement name=\"DO0\"><block type=\"gameOver\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" _expanded=\"1\" _input_init=\"true\"></mutation><field name=\"effect\">effects.confetti</field><value name=\"win\"><shadow type=\"toggleWinLose\"><field name=\"win\">true</field></shadow></value></block></statement></block></next></block></next></block></next></block></statement></block></xml>",
 "main.ts": "namespace SpriteKind {\n    export const Computer = SpriteKind.create()\n}\nsprites.onOverlap(SpriteKind.Player, SpriteKind.Projectile, function (sprite, otherSprite) {\n    otherSprite.destroy()\n    music.knock.play()\n    sprite.startEffect(effects.coolRadial, 1000)\n    info.changeLifeBy(-1)\n})\nsprites.onOverlap(SpriteKind.Player, SpriteKind.Computer, function (sprite, otherSprite) {\n    otherSprite.destroy()\n    music.baDing.play()\n    info.changeScoreBy(1)\n    if (info.score() == 10) {\n        game.over(true, effects.confetti)\n    }\n})\nlet projectile: Sprite = null\nlet mySprite2: Sprite = null\nscene.setBackgroundColor(4)\ngame.splash(\"Save the computers!\", \"Avoid the ninja stars!\")\nlet mySprite = sprites.create(assets.image`ninjaImage`, SpriteKind.Player)\ncontroller.moveSprite(mySprite)\nmySprite.setStayInScreen(true)\ninfo.setScore(0)\ninfo.setLife(3)\ngame.onUpdateInterval(2000, function () {\n    mySprite2 = sprites.create(assets.image`computerImage`, SpriteKind.Computer)\n    mySprite2.setPosition(randint(10, 150), randint(10, 110))\n})\ngame.onUpdateInterval(1000, function () {\n    projectile = sprites.createProjectileFromSide(assets.image`starImage`, randint(-50, 50), randint(-50, 50))\n})\n",
 "pxt.json": "{\n    \"name\": \"GBS - Save the Computers!\",\n    \"description\": \"\",\n    \"dependencies\": {\n        \"device\": \"*\"\n    },\n    \"files\": [\n        \"main.blocks\",\n        \"main.ts\",\n        \"README.md\",\n        \"assets.json\",\n        \"images.g.jres\",\n        \"images.g.ts\"\n    ],\n    \"targetVersions\": {\n        \"branch\": \"v1.8.29\",\n        \"tag\": \"v1.8.29\",\n        \"commits\": \"https://github.com/microsoft/pxt-arcade/commits/d9e3489664e2b8e4c3245a43d28fca1ca5ea001a\",\n        \"target\": \"1.8.29\",\n        \"pxt\": \"7.4.30\"\n    },\n    \"preferredEditor\": \"blocksprj\"\n}\n"
}
```


## Step 1
Begin the project by setting a background color on the screen!


- :tree: Open ``||scene:Scene||`` then drag the ``||scene:set background color||`` block into the ``||loops:on start||`` container already in the editor.


- :paint brush: Click the gray bubble in the ``||scene:set background color||`` block to see the different color options appear. Select a color to use as the background.


- :mouse pointer: Check the Game Window on the right side of the screen to see the selected background color appear!


- :mouse pointer: Click Next to go to the next step.


![Code Ninjas logo](https://github.com/Code-Ninjas-Home-Office/game-building-session-tutorials/blob/master/images/Code_Ninjas_Color_Horizontal_small.jpg?raw=true, "Code Ninjas logo")


```blocks
scene.setBackgroundColor(4)
```


## Step 2
Add a Player sprite to this project!


- :paper plane: Open ``||sprites:Sprites||`` and drag the ``||variables:set mySprite to||`` block into the ``||loops:on start||`` container, below the ``||scene:set background color||`` block.

- :mouse pointer: Now click the gray box and select the **My Assets** tab at the top of the window and Select the ninja image.


- :mouse pointer: Click ▶ to see the Ninja sprite appear in the center of the screen!


![Code Ninjas logo](https://github.com/Code-Ninjas-Home-Office/game-building-session-tutorials/blob/master/images/Code_Ninjas_Color_Horizontal_small.jpg?raw=true, "Code Ninjas logo")


```blocks
scene.setBackgroundColor(4)
let mySprite = sprites.create(assets.image`ninjaImage`, SpriteKind.Player)
```


## Step 3


Code the Player sprite to move around the screen!


- :game: Open ``||controller:Controller||`` and drag the ``||controller:move mySprite with buttons||`` block to the bottom of the ``||loops:on start||`` container.


- :paper plane: Open ``||sprites:Sprites||`` and drag the ``||sprites:set mySprite stay in screen||`` block below the ``||controller:move mySprite with buttons||`` block to keep the Player sprite from moving off screen.


- :mouse pointer: Click ▶ then use the arrow keys to move the Player sprite around the screen.


![Code Ninjas logo](https://github.com/Code-Ninjas-Home-Office/game-building-session-tutorials/blob/master/images/Code_Ninjas_Color_Horizontal_small.jpg?raw=true, "Code Ninjas logo")


```blocks
scene.setBackgroundColor(4)
let mySprite = sprites.create(assets.image`ninjaImage`, SpriteKind.Player)
controller.moveSprite(mySprite)
mySprite.setStayInScreen(true)
```


## Step 4
Add Projectiles for the Player to avoid!


- :circle: Open ``||game:Game||`` and drag the ``||game:on game update every 500 ms||`` container into the editor.


- :paper plane: Open ``||sprites:Sprites||`` and drag the ``||variables:set projectile to||`` block into the ``||game:on game update every 500 ms||`` container. Click the gray box, then select the ninja star image from **My Assets**.


- :mouse pointer: Click ▶ to see a Projectile being launched diagonally every 500 ms.


![Code Ninjas logo](https://github.com/Code-Ninjas-Home-Office/game-building-session-tutorials/blob/master/images/Code_Ninjas_Color_Horizontal_small.jpg?raw=true, "Code Ninjas logo")


```blocks
let projectile: Sprite = null
scene.setBackgroundColor(4)
let mySprite = sprites.create(assets.image`ninjaImage`, SpriteKind.Player)
controller.moveSprite(mySprite)
mySprite.setStayInScreen(true)
game.onUpdateInterval(500, function () {
   projectile = sprites.createProjectileFromSide(assets.image`starImage`, 50, 50)
})
```


## Step 5
Code the Projectile to move in random directions and speeds! 


- :calculator: Open ``||math:Math||`` and drag the ``||math:pick random||`` bubble into the **vx** bubble in the ``||variables:set projectile to||`` block, then replace 0 with -50 and 10 with 50.


- :calculator: Open ``||math:Math||`` again and drag the ``||math:pick random||`` bubble into the **vy** bubble in the ``||variables:set projectile to||`` block, then Replace 0 with -50 and 10 with 50.


- :wrench: Tinker with the number in the ``||game:on game update every 500 ms||`` container to change how often new Projectiles appear.


- :mouse pointer: Click ▶ to see the Projectiles being launched from random places at random speeds!


![Code Ninjas logo](https://github.com/Code-Ninjas-Home-Office/game-building-session-tutorials/blob/master/images/Code_Ninjas_Color_Horizontal_small.jpg?raw=true, "Code Ninjas logo")


```blocks
let projectile: Sprite = null
scene.setBackgroundColor(4)
let mySprite = sprites.create(assets.image`ninjaImage`, SpriteKind.Player)
controller.moveSprite(mySprite)
mySprite.setStayInScreen(true)


game.onUpdateInterval(1000, function () {
   projectile = sprites.createProjectileFromSide(assets.image`starImage`, randint(-50, 50), randint(-50, 50))
})
```


## Step 6
Create a Player sprite to help locate the Ninja sprite!


- :paper plane: Open ``||sprites:Sprites||`` and drag a ``||sprites:on sprite of kind player overlaps otherSprite of kind player||`` container into the editor.

- :mouse pointer:  Keep the first Sprite Kind set to Player, but change the otherSprite Kind  by clicking the ``||sprites:Player ⏷||`` then select **Projectile** from the dropdown.


- :paper plane: Open ``||sprites:Sprites||`` again and drag ``||sprites:destroy mySprite||`` into the ``||sprites:on sprite overlaps otherSprite||`` container.


- :mouse pointer: Drag the ``||variables:otherSprite||`` bubble from the container into the ``||sprites:destroy mySprite||`` block.


- :mouse pointer: Click ▶ to see the Projectile sprite disappear after it overlaps the Player sprite.


![Code Ninjas logo](https://github.com/Code-Ninjas-Home-Office/game-building-session-tutorials/blob/master/images/Code_Ninjas_Color_Horizontal_small.jpg?raw=true, "Code Ninjas logo")


```blocks
sprites.onOverlap(SpriteKind.Player, SpriteKind.Projectile, function (sprite, otherSprite) {
   otherSprite.destroy()
})


let projectile: Sprite = null
scene.setBackgroundColor(4)
let mySprite = sprites.create(assets.image`ninjaImage`, SpriteKind.Player)
controller.moveSprite(mySprite)
mySprite.setStayInScreen(true)


game.onUpdateInterval(1000, function () {
   projectile = sprites.createProjectileFromSide(assets.image`starImage`, randint(-50, 50), randint(-50, 50))
})
```


## Step 7
Add a life ***variable*** to this game!


- :id card: Open ``||info:Info||`` and drag the ``||info:set life to||`` block into the bottom of the ``||loops:on start||`` container.


- :wrench: Tinker with the value in the white bubble to set how many lives the Player sprite will start with.


- :id card: Open ``||info:Info||`` again and drag ``||info:change life by||`` into the ``||sprites:on sprite overlaps otherSprite||`` container. Keep the default value of -1.


- :mouse pointer: Click ▶ to see the life meter change when the Player and Projectile sprites overlap!


![Code Ninjas logo](https://github.com/Code-Ninjas-Home-Office/game-building-session-tutorials/blob/master/images/Code_Ninjas_Color_Horizontal_small.jpg?raw=true, "Code Ninjas logo")


```blocks
sprites.onOverlap(SpriteKind.Player, SpriteKind.Projectile, function (sprite, otherSprite) {
   otherSprite.destroy()
   info.changeLifeBy(-1)
})


let projectile: Sprite = null
scene.setBackgroundColor(4)
let mySprite = sprites.create(assets.image`ninjaImage`, SpriteKind.Player)
controller.moveSprite(mySprite)
mySprite.setStayInScreen(true)
info.setLife(3)


game.onUpdateInterval(1000, function () {
   projectile = sprites.createProjectileFromSide(assets.image`starImage`, randint(-50, 50), randint(-50, 50))
})
```


## Step 8
Make a timer


- :id card: Open ``||info:Info||`` again and drag the ``||info:startCountdown 10||`` container into the ``||loops:on start||`` container.


- :mouse pointer: Click ▶ to see the a countdown timer apper at the top.


- :paper plane: Open ``||info:Info||`` again and drag the ``||info:On Countdown End||`` container into the editor.


- :mouse pointer:  Drag ``||game:Game over ||`` block into the ``||info:On Countdown End||`` container.




![Code Ninjas logo](https://github.com/Code-Ninjas-Home-Office/game-building-session-tutorials/blob/master/images/Code_Ninjas_Color_Horizontal_small.jpg?raw=true, "Code Ninjas logo")


```blocks
info.startCountdown(10)
info.onCountdownEnd(function () {
   game.gameOver(true)
})
```
## Step 9
Complete the project by adding customizations


- :wrench: go ahead and change the game timer to whatever you want.


- :wrench: Try changing the images of the sprites








> Open this page at [https://austin-ag.github.io/shuriken-dodge/](https://austin-ag.github.io/shuriken-dodge/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/austin-ag/shuriken-dodge** and import

## Edit this project ![Build status badge](https://github.com/austin-ag/shuriken-dodge/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/austin-ag/shuriken-dodge** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/austin-ag/shuriken-dodge/raw/master/.github/makecode/blocks.png)

#### Metadata (used for search, rendering)

* for PXT/arcade
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
