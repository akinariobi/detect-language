# Project
## Project Description

*** only for python3+ ***

This is a program which takes your str and returns a language of this.

Does not works with short texts.

Uses the global list of most common words in every language.

UPD// I'll try to make v2 with dict which uses a dict and compare this global_dict with input (+ modifications for chinese, russian, etc.)

You can find text reference in folder "documents".

## Example 

```python
>>> final_detection("Cinq destinations pour jouer à se faire peur Un fort habité par l’âme d’une princesse, un pénitencier à l’abandon où l’on entend encore les prisonniers hurler… Qu’on croie ou non aux esprits, ces lieux ont le mérite d’entretenir le mystère. Et d’être ouverts au public. Si, comme 46 % des Français, vous croyez aux fantômes et autres spectres (Opinion Way, 2014), ces voyages au bout de la peur vous tendent les bras. De Philadelphie au Rajasthan, en passant par la Manche, voici notre sélection de lieux considérés comme hantés. Frissons garantis, surtout lorsqu’on y passe la nuit. 1. Le pénitencier des fous, à Philadelphie (Etats-Unis) L’isolement et le silence. Tel était le lot des prisonniers de l’Eastern State, quand, dans la plupart des autres prisons de l’époque, les malfrats étaient entassés quels que soient leur sexe, leur âge ou leur crime dans les mêmes pièces insalubres. Construit en 1829, le pénitencier tente une nouvelle forme de répression. Les malfrats sont enfermés de manière prolongée dans des cellules individuelles ; lors de leurs déplacements dans les couloirs, ils doivent porter un étrange masque de toile ne laissant apparaître que les yeux. De quoi conduire nombre d’entre eux à la folie. Même si, au XXe siècle, les règles du pénitencier se sont assouplies, quelques âmes tourmentées continuent de hanter ses hauts murs. On raconte que depuis les années 1940, soit trente ans avant la fermeture définitive de l’établissement, des bruits étranges se font entendre dans certaines cellules. S’il est aujourd’hui totalement à l’abandon, le bâtiment est accessible aux visiteurs tous les jours de la semaine. L’atmosphère y est glaçante. Le meilleur moment pour le découvrir est sans doute le week-end suivant la fête d’Halloween, durant lequel est organisée au soir tombé une visite totalement dans le noir, troublée par la présence d’acteurs costumés. Cœurs fragiles, s’abstenir. 2. L’hôtel du crime, en Alberta (Canada) Le Banff Spring a tout d’un décor de cinéma : taille démesurée, luxe désuet et atmosphère inquiétante des grands logis de montagne. Inauguré en 1888 dans le parc naturel de Banff, au beau milieu des Rocheuses, par la Canadian Pacific Railway, il s’imposa durant de longues décennies comme l’un des fleurons de l’hôtellerie canadienne. Aujourd’hui, il n’a rien perdu de sa superbe, rénové et agrémenté d’un spa de haut standing… mais ne se défait pas de sa réputation d’hôtel hanté. L’esprit le plus observé reste à ce jour celui d’une jeune mariée décédée après une chute dans les escaliers, au cours de laquelle des chandeliers auraient aussi mis le feu à sa robe. Plusieurs employés et clients ont raconté l’avoir aperçue à l’endroit précis de son fatal accident et dans la salle de bal, où elle danserait encore parfois, seule. D’autres rumeurs font référence au meurtre d’une famille dans l’une des chambres : les fantômes de ses membres auraient été aperçus plusieurs fois dans le couloir du huitième étage… Les fans de Shining savent désormais où passer leurs prochaines vacances. 3. Le labyrinthe de la peste, à Edimbourg (Ecosse) Sous le Royal Mile et la City Chambers d’Edimbourg se cache un incroyable labyrinthe de ruelles, le Mary King’s Close, édifié au XVIIe siècle. La porte de ce dédale longtemps oublié ne fut rouverte au public qu’en 2003. Evidemment, de vieilles légendes ont alors refait surface, nées après la virulente épidémie de peste qui ravagea la capitale écossaise vers 1645. A l’époque, comme toutes les « closes » (nom donné à ces rues très étroites bordées d’appartements), celle de Mary King était infestée par les rats. Il n’est d’ailleurs pas impossible que le secteur, sillonné par les « médecins de peste » portant un masque en forme de bec, ait été placé en quarantaine. De nombreuses personnes auraient péri dans ce petit périmètre, dont une fillette prénommée Annie, qui reste à ce jour le fantôme le plus célèbre de la « close ». Une chambre entière lui a même été consacrée, dans laquelle les touristes déposent des jouets pour l’apaiser. 4. Le château des chimères, dans la Manche Détruit une première fois pendant la guerre de Cent Ans, le château de Martinvast s’effondra à nouveau sous les bombes lors de la seconde guerre mondiale. Restauré, il est toujours là, comme, visiblement, les revenants qu’il héberge. Chouchouté par le comte de Poutales, son propriétaire, assisté de Brooke Major, une Américaine qui s’occupe du haras qui en dépend, il serait le théâtre de manifestations paranormales régulières : souffles glacés, bruits nocturnes – celui de billes qui s’entrechoquent, comme si des enfants étaient en pleine partie dans les couloirs –, apparitions furtives… Ses occupants en sont persuadés : Martinvast est hanté. Pour en avoir la certitude, ils ont fait appel, il y a quelques années, à un expert, qui a confirmé leur sentiment. Depuis, médiums et équipes de télévision défilent au château. Et le visiteur, qu’il appartienne au camp des sceptiques ou à celui des convaincus, pourra se faire son propre avis en passant une nuit dans l’une des chambres d’hôtes. 5. Le fort maudit du Rajasthan (Inde) Construit durant la deuxième moitié du XVIe siècle, à quelques centaines de kilomètres de Delhi, le fort de Bhangarh domine aujourd’hui un village d’un peu plus de mille âmes, toutes convaincues que le secteur est maudit. Même les rochers le seraient, incitant de nombreux ouvriers à refuser de travailler à la restauration du site. Ce vestige de pierre, entouré de palais et de temples, est un des plus beaux de l’Inde. L’un des plus craints aussi, comme l’indiquent les panneaux à l’entrée du site. Les récits populaires racontent qu’un mage aurait jeté un sort sur le fort, pour punir la princesse de Bhangarh de l’avoir rejeté… et tué. La princesse, assassinée lors d’un massacre, aurait été faite prisonnière dans l’au-delà par le sorcier. Leurs deux fantômes hanteraient désormais les lieux, poussant la municipalité à en interdire la visite après 18 heures. Le fort est situé dans le village de Bhangarh, accessible en voiture et ouvert aux visites de 10 heures à 17 heures.")
```
```python
french
```
###### Algorithm
![alt tag](https://ouzepo.files.wordpress.com/2014/09/jabberwocky_-language-detection-and-gibberish.png)

> Language identification (LI) is a crucial preprocessing step
for natural language processing tasks and other secondary uses of documents
from multilingual sources. Conventional machine learning approaches
to LI perform very well on long documents using standard language,
but relatively poorly on short documents rife with non-standard
orthography. This limitation is an obstacle to secondary uses of social
media data from Twitter and other similar sources. We propose several
linguistically-motivated modifications to the LIGA algorithm, and evaluate
these modifications empirically. Our results show that a modified
algorithm achieves 99.8% accuracy disambiguating among six European
languages, reducing baseline LIGA’s error rate by roughly an order of
magnitude.

More useful information is [HERE](https://www.mitre.org/sites/default/files/pdf/12_2971.pdf)

1) make bigger words library for swedish 
2) solve the problem of french/spanish 
