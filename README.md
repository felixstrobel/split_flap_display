# Split Flap Display

I want a new clock. At the moment I do have an radio cock with some ugly looking numbers. I am a big fan of retro products and thought about a split flap dislay and I liked the idea. Here are some notes and all my documents for the project.

## Definitions

| Name                    | Variable Name | Comment                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| ----------------------- | :-----------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Numbers to be displayed |       n       | The sum of every single number that sould be displayed. In this case for time format (hh:mm) according to German standarts. So 1pm = 11 for example. <ul><li>Drum 1 (**n<sub>1</sub>**): 3 (0-2)</li><li>Drum 2 (**n<sub>2</sub>**): 10 (0-9)</li><li>Drum 3 (**n<sub>3</sub>**): 6 (0-5)</li><li>Drum 4 (**n<sub>4</sub>**): 10 (0-9)</li></ul> All numbers **n<sub>max</sub> = n<sub>1</sub> + n<sub>2</sub> + n<sub>3</sub> + n<sub>4</sub> = 29** |
| Number of plates        | p<sub>n</sub> | The number of plates needed for one drum **p<sub>n</sub> = n * 2**                                                                                                                                                                                                                                                                                                                                                                                    |
| Radius                  |       r       | Radius of the drums **r = 6cm**                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Distance                |       d       | Distance between the hanger of the plates on one drum **d = (2 * pi * r) / p<sub>n</sub>**                                                                                                                                                                                                                                                                                                                                                            |
