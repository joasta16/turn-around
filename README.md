# turn-around
Odwracanie listy
slowo=input("Jakie słowo chcesz odwrócić?: ")
odwrocone_slowo=''
for i in range(len(slowo)-1,-1,-1):
    odwrocone_slowo+=slowo[i]
print(odwrocone_slowo)
