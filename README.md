def firstword(words):
    for i in words:
        firstword = words.split()[0]
        words.find(firstword)
        print(firstword(words))
        return firstword

words = input()

firstword(words)
