print ("scegli un panino\n")
scelta= int(input("Digita 1 per Big Mc\n2 per Mc Chicken\n3 per Crispy McBacon\n"))
spesa= 0
if (scelta==1): #Hai scelto il Big Mc:
	spesa=spesa+7.0
elif(scelta==2): #Hai scelto il Mc Chicken
	spesa=spesa+4.8
elif(scelta==3): #Hai scelto il Crispy McBacon
	spesa=spesa+5.8

print ("SCEGLI UN SECONDO\n")
scelta=int(input("Digita 1 per patatine\n2 per Nuggets\n3 per alette di pollo\n"))
if (scelta==1): #Hai scelto le patatine
	spesa=spesa+3.0
elif(scelta==2): #Hai scelto i Nuggets
	spesa=spesa+4.8
elif(scelta==3): #Hai scelto le alette di pollo
	spesa=spesa+3.5

print ("SCEGLI UN DESSERT\n")
scelta= int(input("Digita 1 per Caffè\n2 per Mc Flurry\n3 per il Milk Shake\n"))
if (scelta==1): #Hai scelto il Caffè
	spesa=spesa+1.2
elif(scelta==2): #Hai scelto il Mc Flurry
	spesa=spesa+2.8
elif(scelta==3): #Hai scelto il Milk Shake
	spesa=spesa+3.5
print("Grazie per aver scelto McDonald il totale è %s" %spesa)
