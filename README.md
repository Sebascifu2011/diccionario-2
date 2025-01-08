meme_words ={
            "cringe":"Algo exepcionalmente raro o embarazoso",
            "lol":"Una respuesta común a algo gracioso",
            "rofl": "una respuesta a una broma",
            "sheesh": "ligera desaprobacion"
            }
while True:
    unknown = input('Esquiba la palabra que no entiende (¡con mayúsculas!):')
    if unknown in meme_words.keys():
        print(meme_words[unknown])
    elif unknown == '0':
        break
    else:
        print('palabra o valor no identificado por favor vuelva mas tarde y verifice otra vez')
