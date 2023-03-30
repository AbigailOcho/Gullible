# Gullible
A game using input validation and loops

print('Gullible, by Al Sweigart al@inventwithpython.com, recoded in MU Editor by Abigail Ochoa')

while True:
    print('Do you want to know how to keep a gullible person busy for hours? Y/N')
    response = input('> ')
    if response.lower() == 'no' or response.lower() ==  'n':
        break
    if response.lower() == 'yes' or response.lower() == 'y':
        continue
        print('"{}" is not a valid yes/no response.'.format(responses))

print('Thank you, Have a nice day!')
