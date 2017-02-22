<!--

Hint 2

-->
grep -r "CLUE" *

//***
Crimescene:CLUE: Footage from an ATM security camera is blurry but shows that the perpetrator is a tall male, at least 6'.
crimescene:CLUE: Found a wallet believed to belong to the killer: no ID, just loose change, and membership cards for AAA, Delta SkyMiles, the local library, and the Museum of Bash History. The cards are totally untraceable and have no name, for some reason.
crimescene:CLUE: Questioned the barista at the local coffee shop. He said a woman left right before they heard the shots. The name on her latte was Annabel, she had blond spiky hair and a New Zealand accent.
***//

<!--
Hint 4
-->

grep -r "Annabel" *

memberships/AAA:Annabel Church
memberships/AAdvantage:Annabel Fuglsang
memberships/AAdvantage:Annabel Church
memberships/Fitness_Galaxy:Oluwasegun Annabel
memberships/Fitness_Galaxy:Annabel Church
memberships/Museum_of_Bash_History:Annabel Church
memberships/Museum_of_Bash_History:Oluwasegun Annabel
memberships/REI:Annabel Church
memberships/Rotary_Club:Annabel Sun
memberships/Rotary_Club:Annabel Fuglsang
memberships/Rotary_Club:Annabel Church
people:Annabel Sun  F 26  Hart Place, line 40
people:Oluwasegun Annabel M 37  Mattapan Street, line 173
people:Annabel Church F 38  Buckingham Place, line 179
people:Annabel Fuglsang M 40  Haley Street, line 176
vehicles:Owner: Oluwasegun Annabel
vehicles:Owner: Annabel Church
vehicles:Owner: Annabel Sun
vehicles:Owner: Annabel Fuglsang

grep -A 5 "L337" vehicles | grep -C 5 "6'"


head -n 173 streets/Mattapan_Street | tail -n 1
SEE INTERVIEW #9437737

<!-- HINT 5 -->
cat interview-9437737
Doesn't appear to be the witness from the cafe, who is female.


<!-- Hint 1
Hint 3

Addreses are in the people file
-->
head -n 20 people



NAME  GENDER  AGE ADDRESS
Alicia Fuentes  F 48  Walton Street, line 433
Jo-Ting Losev F 46  Hemenway Street, line 390
Elena Edmonds F 58  Elmwood Avenue, line 123
Naydene Cabral  F 46  Winthrop Street, line 454
Dato Rosengren  M 22  Mystic Street, line 477
Fernanda Serrano  F 37  Redlands Road, line 392
Emiliano Wenk M 90  Paulding Street, line 490
Larry Lapin M 71  Atwill Road, line 298
Jakub Gondos  M 61  Mitchell Street, line 187
Derek Kazanin M 55  Tennis Road, line 440
Jens Tuimalealiifano  M 83  Rockwood Street, line 205
Nikola Kadhi  M 75  Glenville Avenue, line 226


<!--
Hint 6
Hint 7
-->
grep -A 5 "L337" vehicles | grep -C 5 "6'"


License Plate L337QE9
Make: Honda
Color: Blue
Owner: Erika Owens
Height: 6'5"
Weight: 220 lbs
--

--
License Plate L337539
Make: Honda
Color: Blue
--
--
--

--
License Plate L337369
Make: Honda
Color: Blue
--
--
--
License Plate L337DV9
Make: Honda
Color: Blue
Owner: Joe Germuska
Height: 6'2"
Weight: 164 lbs

License Plate L3375A9
Make: Honda
Color: Blue
Owner: Jeremy Bowers
Height: 6'1"
Weight: 204 lbs

License Plate L337WR9
Make: Honda
Color: Blue
Owner: Jacqui Maher
Height: 6'2"
Weight: 130 lbs


<!--

Hint 5
-->
head -n Mattapan_Street | tail -n 1
SEE INTERVIEW #9437737

<!--
Hint 8
-->

grep -r "Joe Germuska" *
AAA:Joe Germuska
Terminal_City_Library:Joe Germuska

grep -r "Jeremy Bowers" *
AAA:Jeremy Bowers
Delta_SkyMiles:Jeremy Bowers
Museum_of_Bash_History:Jeremy Bowers
Terminal_City_Library:Jeremy Bowers









