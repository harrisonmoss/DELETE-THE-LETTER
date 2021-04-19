letter = input('step 1: Enter letter(s):')
letter2 = input('step 2: enter the letters to replace step 1 letters:')
file = open("doc.txt")
content = (file.read())
done = content.replace(letter, letter2)

print(done)
