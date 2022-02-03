sprites.onOverlap(SpriteKind.Player, SpriteKind.Enemy, function (sprite, otherSprite) {
    Enemy1.sayText("" + text_list[randint(0, text_list.length - 1)])
    pause(100)
    Runner.destroy()
    pause(1000)
    game.over(false)
})
let text_list: string[] = []
let Enemy1: Sprite = null
let Runner: Sprite = null
Runner = sprites.create(img`
    . . . . . . 2 . . . . 2 . . . . 
    . . . . . 5 5 5 . . 5 5 5 . . . 
    . . . . 4 4 4 4 4 4 4 4 4 . . . 
    . . . 8 8 8 8 8 8 8 8 8 8 . . . 
    . . 8 8 8 f 8 8 8 8 f 8 8 . . . 
    . 8 8 8 8 8 8 8 8 8 8 8 8 . . . 
    8 8 8 2 8 8 8 8 8 2 8 8 8 . . . 
    8 8 8 2 2 2 2 2 2 2 8 8 8 . . . 
    . 8 8 8 8 8 8 8 8 8 8 8 8 . . . 
    . 8 8 8 8 8 8 8 8 8 8 8 8 . . . 
    . . 8 8 8 . . . . 8 8 8 . . . . 
    . . 8 8 8 . . . . 8 8 8 . . . . 
    . . 8 8 8 . . . . 8 8 8 . . . . 
    . . 8 8 8 . . . . 8 8 8 . . . . 
    . . 8 8 8 . . . . 8 8 8 . . . . 
    . . 8 8 8 . . . . 8 8 8 . . . . 
    `, SpriteKind.Player)
Runner.setPosition(35, 58)
controller.moveSprite(Runner)
Enemy1 = sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . b 5 5 b . . . 
    . . . . . . b b b b b b . . . . 
    . . . . . b b 5 5 5 5 5 b . . . 
    . b b b b b 5 5 5 5 5 5 5 b . . 
    . b d 5 b 5 5 5 5 5 5 5 5 b . . 
    . . b 5 5 b 5 d 1 f 5 d 4 f . . 
    . . b d 5 5 b 1 f f 5 4 4 c . . 
    b b d b 5 5 5 d f b 4 4 4 4 b . 
    b d d c d 5 5 b 5 4 4 4 4 4 4 b 
    c d d d c c b 5 5 5 5 5 5 5 b . 
    c b d d d d d 5 5 5 5 5 5 5 b . 
    . c d d d d d d 5 5 5 5 5 d b . 
    . . c b d d d d d 5 5 5 b b . . 
    . . . c c c c c c c c b b . . . 
    `, SpriteKind.Enemy)
text_list = [
"L",
"Get Better Noob",
"Bye",
"Can't Touch This",
"Adios"
]
