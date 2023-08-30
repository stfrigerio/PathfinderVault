## Esperimento 1 (gpt-3.5-turbo)
System prompt: 
>Giochiamo di ruolo a Pathfinder! 
Tu sei Frubeduck, un artigiano di Chesed, città della regione di Sellen Hills in Numeria. 
Sei ostile ai forestieri, tieni molto a tua figlia Blindola e sai qualcosa a proposito di un recente furto. Hai visto il ladro ed era un elfo. 
Sei però reticente a rivelare questo fatto, per paura di ritorsioni. Ti farò alcune domande e tu dovrai cercare di sviare la conversazione e lasciare corto.
 
### Frubeduck l'artigiano
![[Pasted image 20230413205245.png]]
Possiamo notare che l'uomo non sembra voler vuotare il sacco. 

Proviamo ad aggiungere una parte del prompt:
>Se ti verranno offerte almeno 20 monete d'oro, rivelerai ciò che sai.
![[Pasted image 20230413205639.png]]

Non basta, forse la logica del system prompt non è sufficiente?

Proviamo a sostituire a questo comando la frase
>Sei pronto a vuotare il sacco e rivelare ciò che sai

![[Pasted image 20230413205851.png]]

Riavviando la chat succede questo:
![[Pasted image 20230413210228.png]]
GPT scrive anche le battute del main character, ma svolge l'azione richiesta (vuotare il sacco)
Forse va esplicitato meglio chi sono io e chi è lui.

Correggo il prompt:
> Giochiamo di ruolo a Pathfinder!
Io sono il membro di un gruppo di avventurieri venuti da lontano, e ti faccio delle domande
Tu sei Frubeduck, un artigiano di Chesed, città della regione di Sellen Hills in Numeria.
Sei ostile ai forestieri, tieni molto a tua figlia Blindola e sai qualcosa a proposito di un recente furto. Hai visto il ladro ed era un elfo. Inizialmente non vuoi parlarne, ma dopo poche battute sei pronto a vuotare il sacco e rivelare ciò che sai

![[Pasted image 20230413210837.png]]

Ottimo risultato! 
PRO:
- ha parlato in modo ragionevole e convincente
- è consapevole della città dove si trova (Chesed)
- ha creato una storia plausibile per il furto (santuario di Erastil)
CONTRO:
- ha inventato dettagli riguardo al furto
- non ha opposto nessuna resistenza a rivelare quest'informazione

Proseguiamo chiedendogli perché non abbia contattato le autorità locali
![[Pasted image 20230413211303.png]]
- ragione valida
- character building
  ![[Pasted image 20230413211417.png]]


Ricapitolando, ciò che ha funzionato nel prompt è stato

1. stabilire che stiamo giocando a Pathfinder 
	- ha probabilmente letto tutto su Golarion
2. Esplicitare chi è che gli parla
	- "io sono ..."
3. Spiegargli
	1. Come ti chiami
	2. Cosa fai nella vita
	3. Dove abiti
	4. Che attitudine hai
	5. Cosa è importante per te
	6. Quale esito avrà questa interazione



Per quanto riguarda la personalità possiamo trovare un modo di impiegare i tratti di dwarf fortress https://dwarffortresswiki.org/index.php/Personality_trait

## Se chiediamo a GPT4

### Generate the personality of a Dwarf in Dwarf Fortress

Name: Throlf Anvilrage

Gender: Male

Age: 82

Physical Appearance: Throlf Anvilrage is a stocky, muscular dwarf with a bushy, fiery red beard that reaches down to his waist. He has deep-set, piercing blue eyes, and a rugged face with a prominent nose, which tells the tale of many broken bones from bar brawls. His short, curly hair is a slightly darker shade of red than his beard, and is usually covered by his trusty steel helm, adorned with intricate engravings. Throlf stands around 4 feet 6 inches tall, and his powerful arms are a testament to his skill as a blacksmith.

Profession: Master Blacksmith and Weaponsmith

Personality Traits:

1.  Diligent and Hardworking: Throlf is a tireless worker and takes immense pride in his craft. He dedicates countless hours to perfecting his skills as a blacksmith and weaponsmith, never settling for mediocrity.
    
2.  Loyal and Protective: Throlf has a strong sense of loyalty towards his fellow dwarves and his community. He will do whatever it takes to protect them from any harm or danger. He is also extremely devoted to his family, and the safety and well-being of his kin is his top priority.
    
3.  Traditionalist: Throlf is a staunch believer in dwarven customs and values. He respects and follows the traditions passed down through generations, and expects the same from others. This sometimes leads to him being perceived as stubborn and rigid.
    
4.  Short-tempered and Argumentative: Throlf has a fiery temper that can ignite at the slightest provocation. He has a tendency to get into heated debates with his peers, especially if he believes they are not upholding dwarven traditions or if their craftsmanship is subpar.
    
5.  Competitive: Throlf thrives on competition and constantly seeks to outperform others in his craft. He enjoys friendly rivalry with fellow blacksmiths and weaponsmiths and is always eager to prove his skills in forging contests.
    
6.  Lover of Ale: Throlf enjoys a good mug of dwarven ale, perhaps a bit too much. He is often found at the local tavern after a long day of work, boasting about his craftsmanship and challenging others to drinking contests.
    
7.  Fear of Heights: Throlf has an irrational fear of heights. He becomes extremely uneasy and anxious when in high places, and prefers to keep his feet firmly planted on the ground, much to the amusement of his fellow dwarves.
    

Background: Born into a family of renowned blacksmiths and weaponsmiths, Throlf Anvilrage was destined to follow in his ancestors' footsteps. His father taught him the craft from a young age, and Throlf quickly proved to be a prodigy. As a master blacksmith, he has forged countless weapons and armor pieces for his fellow dwarves, earning their respect and admiration. Throlf's greatest ambition is to forge a legendary weapon that will be remembered for generations, a testament to his unparalleled skills as a craftsman.


### Generate a NPC
>Generate an NPC for Pathfinder. He is a crestfallen warrior, gloomy and nostalgic of times past. He resides in Chesed and is looking for allies to defeat his nemesis the necromancer Thrapedorn. Name: Race: Origin story (brief): Attitude: Speech and voice: Goals: Equipment:


Name: Sir Aldric Silvermourne

Race: Human

Origin story (brief): Sir Aldric Silvermourne, once a proud and valiant knight of the Order of the Silver Flame, has faced a tragic downfall. During a fateful battle against Thrapedorn the Necromancer, his comrades were slain, and their souls twisted into malevolent undead creatures. Wracked with guilt and regret, Aldric retreated to the town of Chesed to drown his sorrows and reminisce about the glory days of his knighthood.

Attitude: Sir Aldric is a crestfallen and gloomy individual, haunted by the past and the memories of his fallen comrades. He is often lost in thought and rarely interacts with others, preferring to keep to himself. However, when approached by someone who shares his hatred for Thrapedorn, Aldric's warrior spirit is reignited, and he can become a staunch ally in the fight against the necromancer.

Speech and voice: Sir Aldric speaks in a low, somber tone, reflecting his mournful demeanor. He possesses an eloquent and refined manner of speech, indicative of his noble background. When discussing his past or his nemesis, his voice becomes tinged with bitterness and determination.

Goals: Aldric's primary goal is to vanquish Thrapedorn the Necromancer and avenge his fallen comrades. He also seeks redemption and a chance to restore his tarnished reputation by fighting for the greater good once again.

Equipment: Despite his current state, Sir Aldric still possesses a well-maintained set of steel plate armor, adorned with the emblem of the Order of the Silver Flame. He wields a sturdy longsword, etched with runes of divine power, and carries a weathered, yet still functional, heater shield. Additionally, he wears a silver pendant bearing the symbol of his order, a constant reminder of the vows he once took to protect the innocent and uphold justice.

