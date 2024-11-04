#Lun Ascensao Tony 1G05

# ce qui a été implémenté (j'ai codé le présent etc.. j'ai géré les verbes type manger etc....)


def conjuguer(verbe, mode, temps, auxiliaire):

        if verbe[-2:]=="er":
            radical=verbe[:-2]
            participe=verbe[:-2]+"é"
            
            if mode=="indicatif":

                if temps=="présent":

                    if verbe[-3]=="g":
                        print("je "+radical+"e")
                        print("tu "+radical+"es")
                        print("il/elle/on "+radical+"e")
                        print("nous "+radical+"eons")
                        print("vous "+radical+"ez")
                        print("ils/elles "+radical+"ent")

                    elif verbe[-4:]=="ecer":
                        print("je "+radical[:-2]+"è"+radical[-1]+"e")
                        print("tu "+radical[:-2]+"è"+radical[-1]+"es")
                        print("il/elle/on "+radical[:-2]+"è"+radical[-1]+"e")
                        print("nous "+radical[:-1]+"çons")
                        print("vous "+radical[:-1]+"çez")
                        print("ils/elles "+radical[:-2]+"è"+radical[-1]+"ent")

                    elif verbe[-3]=="c":
                        print("je "+radical+"e")
                        print("tu "+radical+"es")
                        print("il/elle/on "+radical+"e")
                        print("nous "+radical[:-1]+"çons")
                        print("vous "+radical+"ez")
                        print("ils/elles "+radical+"ent")

                    elif verbe[-4:]=="eler":
                        print("je "+radical+"le")
                        print("tu "+radical+"les")
                        print("il/elle/on "+radical+"le")
                        print("nous "+radical+"ons")
                        print("vous "+radical+"ez")
                        print("ils/elles "+radical+"lent")

                    elif verbe[-4:]=="eter":
                        print("je "+radical+"te")
                        print("tu "+radical+"tes")
                        print("il/elle/on "+radical+"te")
                        print("nous "+radical[:-1]+"ons")
                        print("vous "+radical+"ez")
                        print("ils/elles "+radical+"tent")

                    elif verbe[-4:]=="eyer":
                        print("je "+radical+"e")
                        print("tu "+radical+"es")
                        print("il/elle/on "+radical+"e")
                        print("nous "+radical+"ons")
                        print("vous "+radical+"ez")
                        print("ils/elles "+radical+"ent")

                    elif verbe[-4:]=="uyer" or verbe[-4:]=="ayer" or verbe[-4:]=="oyer":
                        print("je "+radical[:-1]+"ie")
                        print("tu "+radical[:-1]+"ies")
                        print("il/elle/on "+radical[:-1]+"ie")
                        print("nous "+radical[:-1]+"yons")
                        print("vous "+radical[:-1]+"yez")
                        print("ils/elles "+radical[:-1]+"ient")

                    elif verbe[-4:]=="emer" or verbe[-4:]=="eper" or verbe[-4:]=="erer" or verbe[-4:]=="eser" or verbe[-4:]=="ever":
                        print("je "+radical[:-2]+"è"+radical[-1]+"e")
                        print("tu "+radical[:-2]+"è"+radical[-1]+"es")
                        print("il/elle/on "+radical[:-2]+"è"+radical[-1]+"e")
                        print("nous "+radical[:-1]+radical[-1]+"ons")
                        print("vous "+radical[:-1]+radical[-1]+"ez")
                        print("ils/elles "+radical[:-2]+"è"+radical[-1]+"ent")

                    elif verbe[-5:]=="evrer":
                        print("je "+radical[:-3]+"èvre")
                        print("tu "+radical[:-3]+"èvres")
                        print("il/elle/on "+radical[:-3]+"èvre")
                        print("nous "+radical[:-2]+"vrons")
                        print("vous "+radical[:-2]+"vrez")
                        print("ils/elles "+radical[:-3]+"èvrent")

                    elif verbe[-4:]=="écer" or verbe[-4:]=="éder" or verbe[-4:]=="éler" or verbe[-4:]=="émer" or verbe[-4:]=="éner" or verbe[-4:]=="érer" or verbe[-4:]=="éser" or verbe[-4:]=="éter" or verbe[-4:]=="éyer":
                        print("je "+radical[:-2]+"è"+radical[-1]+"e")
                        print("tu "+radical[:-2]+"è"+radical[-1]+"es")
                        print("il/elle/on "+radical[:-2]+"è"+radical[-1]+"e")
                        print("nous "+radical[:-1]+radical[-1]+"ons")
                        print("vous "+radical[:-1]+radical[-1]+"ez")
                        print("ils/elles "+radical[:-2]+"è"+radical[-1]+"ent")

                    elif verbe[-5:]=="ébrer" or verbe[-5:]=="écher" or verbe[-5:]=="écrer" or verbe[-5:]=="égler" or verbe[-5:]=="égner" or verbe[-5:]=="égrer" or verbe[-5:]=="éguer" or verbe[-5:]=="équer" or verbe[-5:]=="étrer" or verbe[-5:]=="évrer":
                        print("je "+radical[:-3]+"è"+radical[-2]+radical[-1]+"e")
                        print("tu "+radical[:-3]+"è"+radical[-2]+radical[-1]+"es")
                        print("il/elle/on "+radical[:-3]+"è"+radical[-2]+radical[-1]+"e")
                        print("nous "+radical+"ons")
                        print("vous "+radical+"ez")
                        print("ils/elles "+radical[:-3]+"è"+radical[-2]+radical[-1]+"ent")

                    else :
                        print("je "+radical+"e")
                        print("tu "+radical+"es")
                        print("il/elle/on "+radical+"e")
                        print("nous "+radical+"ons")
                        print("vous "+radical+"ez")
                        print("ils/elles "+radical+"ent")

                if temps=="futur":

                    if verbe[-4:]=="eler" or verbe[-4:]=="eter":
                        print("je "+radical+verbe[-3]+"erai")
                        print("tu "+radical+verbe[-3]+"eras")
                        print("il/elle/on "+radical+verbe[-3]+"era")
                        print("nous "+radical+verbe[-3]+"erons")
                        print("vous "+radical+verbe[-3]+"erez")
                        print("ils/elles "+radical+verbe[-3]+"eront")

                    elif verbe[-5:]=="voyer":
                        print
                        print
                        print
                        print
                        print
                        print

                    elif verbe[-4:]=="oyer" or verbe[-4:]=="uyer" or verbe[-4:]=="iyer":
                        print("je "+radical[:-1]+"ierai")
                        print("tu "+radical[:-1]+"ieras")
                        print("il/elle/on "+radical[:-1]+"iera")
                        print("nous "+radical[:-1]+"ierons")
                        print("vous "+radical[:-1]+"ierez")
                        print("ils/elles "+radical[:-1]+"ieront")

                    else :
                        print("je "+verbe+"ai")
                        print("tu "+verbe+"as")
                        print("il/elle/on "+verbe+"a")
                        print("nous "+verbe+"ons")
                        print("vous "+verbe+"ez")
                        print("ils/elles "+verbe+"ont")

                if temps=="imparfait":

                    if verbe[-3]=="g":
                        print("je "+radical+"eais")
                        print("tu "+radical+"eais")
                        print("il/elle/on "+radical+"eait")
                        print("nous "+radical+"ions")
                        print("vous "+radical+"iez")
                        print("ils/elles "+radical+"eaient")

                    elif verbe[-3]=="c":
                        print("je "+radical[:-1]+"çais")
                        print("tu "+radical[:-1]+"çais")
                        print("il/elle/on "+radical[:-1]+"çait")
                        print("nous "+radical+"ions")
                        print("vous "+radical+"iez")
                        print("ils/elles "+radical[:-1]+"çaient")

                    else :
                        print("je "+radical+"ais")
                        print("tu "+radical+"ais")
                        print("il/elle/on "+radical+"ait")
                        print("nous "+radical+"ions")
                        print("vous "+radical+"iez")
                        print("ils/elles "+radical+"aient")

                if temps=="passé simple":
                    
                    if verbe[-3]=="g":
                        print
                        print
                        print
                        print
                        print
                        print

                    if verbe[-3]=="c":
                        print
                        print
                        print
                        print
                        print
                        print

                    else:
                        print("je "+radical+"ai")
                        print("tu "+radical+"as")
                        print("il/elle/on "+radical+"a")
                        print("nous "+radical+"âmes")
                        print("vous "+radical+"âtes")
                        print("ils/elles "+radical+"èrent")
