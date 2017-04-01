Real-life Trial Deception Detection Dataset
============================================
Veronica Perez-Rosas, Mohamed Abouelenien, Rada Mihalcea, Mihai Burzo
Language and Information Technologies
University of Michigan

vrncapr@umich.edu
zmohamed@umich.edu
mihalcea@umich.edu
mburzo@umich.edu

Version 1.0
January 2016
-----------------------------------------------------------------
1. Introduction
This document describes the datasets used in the paper: Deception Detection using Real-life Trial Data (Perez-Rosas et. al, 2015).

-----------------------------------------------------------------
2. Content
The archive contains three folders and one README file. The README (this file) contains information about the data collected and their sources as well as citation and acknowledgements information.
The folders are as follows:
1- Clips: The folder includes two sub-folders containing the deceptive and truthful clips. 
2- Transcription: The folder includes two sub-folders containing the deceptive and truthful transcriptions. 
3- Gesture annotation: The folder contains the gesture annotation in one .csv file. The first column includes the clip ID and the last column includes the class label whether deceptive or truthful. The rest of the columns include binary features representing the existence of a certain gesture category as (1) and the absence of the gesture as (0). The first row includes the labels of the gesture categories. 

-----------------------------------------------------------------
3. Dataset Information
The dataset consists of real-life trial videos that are publicly available on YouTube channels and other public websites. The dataset also contains statements made by exonerees after exoneration and a few statements from defendants during crime-related TV episodes. The speakers in the videos are either defendants or witnesses. The video clips are labeled as deceptive or truthful based on a guilty verdict, not-guilty verdict, and exoneration. More details are available in the paper that introduced the dataset (Perez-Rosas et al, 2015; full reference below).

The dataset consists of 121 videos including 61 deceptive and 60 truthful trial clips. The average length of the videos in the dataset is 28.0 seconds. The average video length is 27.7 seconds and 28.3 seconds for the deceptive and truthful clips, respectively. The data consists of 21 unique female and 35 unique male speakers, with their ages approximately ranging between 16 and 60 years.

-----------------------------------------------------------------
4. Dataset structure
The following two tables list the details of the deceptive and truthful video clips:
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| Deceptive Trials  | Role / trial name                              | Ruling                                                                            | Link if available                                   |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_001.mp4 | Defendant / Amanda Hayes                       | Guilty                                                                            | https://www.youtube.com/user/croakerqueen123/videos |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_002.mp4 | Defendant / Amanda Hayes                       | Guilty                                                                            | https://www.youtube.com/user/croakerqueen123/videos |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_003.mp4 | Defendant / Amanda Hayes                       | Guilty                                                                            | https://www.youtube.com/user/croakerqueen123/videos |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_004.mp4 | Defendant / Amanda Hayes                       | Guilty                                                                            | https://www.youtube.com/user/croakerqueen123/videos |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_005.mp4 | Defendant / Amanda Hayes                       | Guilty                                                                            | https://www.youtube.com/user/croakerqueen123/videos |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_006.mp4 | Defendant / Amanda Hayes                       | Guilty                                                                            | https://www.youtube.com/user/croakerqueen123/videos |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_007.mp4 | Defendant / Andrea Sneiderman                  | Guilty                                                                            | https://www.youtube.com/watch?v=zJvJ-2H7iTg         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_008.mp4 | Defendant / Andrea Sneiderman                  | Guilty                                                                            | https://www.youtube.com/watch?v=zJvJ-2H7iTg         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_009.mp4 | Defendant / Andrea Sneiderman                  | Guilty                                                                            | https://www.youtube.com/watch?v=zJvJ-2H7iTg         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_010.mp4 | Defendant / Andrea Sneiderman                  | Guilty                                                                            | https://www.youtube.com/watch?v=zJvJ-2H7iTg         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_011.mp4 | Defendant / Andrea Sneiderman                  | Guilty                                                                            | https://www.youtube.com/watch?v=zJvJ-2H7iTg         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_012.mp4 | Defendant / Andrea Sneiderman                  | Guilty                                                                            | https://www.youtube.com/watch?v=zJvJ-2H7iTg         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_013.mp4 | Defendant / Andrea Sneiderman                  | Guilty                                                                            | https://www.youtube.com/watch?v=zJvJ-2H7iTg         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_014.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_015.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_016.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_017.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_018.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_019.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_020.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_021.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_022.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_023.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_024.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_025.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_026.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_027.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_028.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_029.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_030.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_031.mp4 | Defendant / Jodi Arias                         | Guilty                                                                            | https://www.youtube.com/watch?v=ICV2A7gVHf4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_032.mp4 | Defendant / Donna Scrivo                       | Guilty                                                                            | https://www.youtube.com/watch?v=w8oaUlhga1g         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_033.mp4 | Defendant / Jamie Hood                         | Guilty                                                                            | https://www.youtube.com/watch?v=PwkVJ00WBJ4         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_034.mp4 | Defense witness / Jamie Hood                   | Guilty                                                                            | https://www.youtube.com/watch?v=SKl-oGTrfRg         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_035.mp4 | Defendant /  Mitchelle Blair                   | Guilty                                                                            | https://www.youtube.com/watch?v=hjzNZyF6Arc         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_036.mp4 | Defendant / Marissa Devault                    | Guilty                                                                            | https://www.youtube.com/watch?v=BNOgC4FSbQA         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_037.mp4 | Defendant / Crystal Mangum                     | Guilty                                                                            | https://www.youtube.com/watch?v=t3nuzZR6tUw         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_038.mp4 | Defendant / Crystal Mangum                     | Guilty                                                                            | https://www.youtube.com/watch?v=t3nuzZR6tUw         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_039.mp4 | Defendant / Crystal Mangum                     | Guilty                                                                            | https://www.youtube.com/watch?v=t3nuzZR6tUw         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_040.mp4 | Defendant / Crystal Mangum                     | Guilty                                                                            | https://www.youtube.com/watch?v=t3nuzZR6tUw         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_041.mp4 | Police Spokesman / Robert Dziekanski           | Guilty                                                                            | https://www.youtube.com/watch?v=Wh56s4KWAJE         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_042.mp4 | Police Spokesman / Robert Dziekanski           | Guilty                                                                            | https://www.youtube.com/watch?v=o5k7CmAENHo         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_043.mp4 | Police Spokesman / Robert Dziekanski           | Guilty                                                                            | https://www.youtube.com/watch?v=WxQxMNEl-SE         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_044.mp4 | Mayor / Dyches, Hall, and Hopkins trial        | Police lied about attacking men, a video showed they were lying. They were fired. | https://www.youtube.com/watch?v=5JnwEYTWCgM         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_045.mp4 | Kelly Burke                                    | Said information was not publicly available. Link showed it was available.        | https://www.youtube.com/watch?v=iO6lrx-4gYg         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_046.mp4 | Officer Witness of prosecution / Carlos Miller | Not Guilty                                                                        | https://www.youtube.com/watch?v=nVyU5nHwmwQ         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_047.mp4 | Officer Witness of prosecution / Carlos Miller | Not Guilty                                                                        | https://www.youtube.com/watch?v=nVyU5nHwmwQ         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_048.mp4 | Officer Witness of prosecution / Carlos Miller | Not Guilty                                                                        | https://www.youtube.com/watch?v=nVyU5nHwmwQ         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_049.mp4 | Officer Witness of prosecution / Carlos Miller | Not Guilty                                                                        | https://www.youtube.com/watch?v=nVyU5nHwmwQ         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_050.mp4 | Defendant / Marissa Devault                    | Guilty                                                                            | https://www.youtube.com/watch?v=nY-7ptqVrqY         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_051.mp4 | Lawyer / Marissa Devault                       | Guilty                                                                            | https://www.youtube.com/watch?v=nY-7ptqVrqY         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_052.mp4 | Defendant's statement / Scott Peterson         | Guilty                                                                            | https://www.youtube.com/watch?v=_B1eiwSGEic         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_053.mp4 | Defendant / Michael Dunn                       | Guilty                                                                            | https://www.youtube.com/watch?v=jB4MWOUi2t8         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_054.mp4 | Defense Witness / Jodi Arias                   | Guilty                                                                            | https://www.youtube.com/watch?v=bvv-ZwcyID0         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_055.mp4 | Defense Witness / Jodi Arias                   | Guilty                                                                            | https://www.youtube.com/watch?v=hbAPN4LOsdg         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_056.mp4 | Defense Witness / Jodi Arias                   | Guilty                                                                            | https://www.youtube.com/watch?v=WWqQsi6OK8E         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_057.mp4 | Defense Witness / Jodi Arias                   | Guilty                                                                            | https://www.youtube.com/watch?v=WWqQsi6OK8E         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_058.mp4 | Defendant /  Lance Armstrong                   | after lying previously, he publicly admitted to doping, case still going on.      | https://www.youtube.com/watch?v=c96qIK5uwNg         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_059.mp4 | Defendant / Candace Conti                      | Guilty                                                                            | https://www.youtube.com/watch?v=QOBXT9CZxzI         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_060.mp4 | Defendant / Candace Conti                      | Guilty                                                                            | https://www.youtube.com/watch?v=OPcYn4AiwQE         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+
| trial_lie_061.mp4 | Defendant / Candace Conti                      | Guilty                                                                            | https://www.youtube.com/watch?v=eoIh5_EGblA         |
+-------------------+------------------------------------------------+-----------------------------------------------------------------------------------+-----------------------------------------------------+




+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| Truthful Trials     | Role / trial name                       | Ruling                      | Link if available                           |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_001.mp4 | Lawyer / The innocence project          |  NA                         |  http://www.innocenceproject.org            |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_002.mp4 | Lawyer / The innocence project          |  NA                         |  http://www.innocenceproject.org            |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_003.mp4 | Defendant / Andrea Sneiderman           | Guilty                      | https://www.youtube.com/watch?v=zJvJ-2H7iTg |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_004.mp4 | Defendant / Andrea Sneiderman           | Guilty                      | https://www.youtube.com/watch?v=zJvJ-2H7iTg |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_005.mp4 | Defendant / Andrea Sneiderman           | Guilty                      | https://www.youtube.com/watch?v=zJvJ-2H7iTg |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_006.mp4 | Defendant / Andrea Sneiderman           | Guilty                      | https://www.youtube.com/watch?v=zJvJ-2H7iTg |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_007.mp4 | Defendant / Andrea Sneiderman           | Guilty                      | https://www.youtube.com/watch?v=zJvJ-2H7iTg |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_008.mp4 | Witness / Jodi Arias                    | Guilty                      | https://www.youtube.com/watch?v=FT28C3b5GKA |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_008.mp4 | Witness / Jodi Arias                    | Guilty                      | https://www.youtube.com/watch?v=FT28C3b5GKA |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_010.mp4 | Witness / Jodi Arias                    | Guilty                      | https://www.youtube.com/watch?v=FT28C3b5GKA |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_011.mp4 | Witness / Jodi Arias                    | Guilty                      | https://www.youtube.com/watch?v=FT28C3b5GKA |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_012.mp4 | Witness / Jodi Arias                    | Guilty                      | https://www.youtube.com/watch?v=FT28C3b5GKA |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_013.mp4 | Witness / Jodi Arias                    | Guilty                      | https://www.youtube.com/watch?v=FT28C3b5GKA |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_014.mp4 | Witness / Jodi Arias                    | Guilty                      | https://www.youtube.com/watch?v=FT28C3b5GKA |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_015.mp4 | Witness / Jodi Arias                    | Guilty                      | https://www.youtube.com/watch?v=FT28C3b5GKA |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_016.mp4 | Defendant / Fernando Bermudez           | Exonerated                  | https://www.youtube.com/watch?v=POzozR1-xRc |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_017.mp4 | Defendant / Fernando Bermudez           | Exonerated                  | https://www.youtube.com/watch?v=POzozR1-xRc |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_018.mp4 | Defendant / Chris Ochoa                 | Exonerated                  | https://www.youtube.com/watch?v=0xJlsxCGw9w |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_019.mp4 | Defendant / Chris Ochoa                 | Exonerated                  | https://www.youtube.com/watch?v=0xJlsxCGw9w |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_020.mp4 | Defendant / Steven Barnes               | Exonerated                  | https://www.youtube.com/watch?v=XhjGV7qATWw |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_021.mp4 | Defendant / Randy Mills                 | Exonerated                  | https://www.youtube.com/watch?v=hxJ3CmPKn6I |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_022.mp4 | Defendant / Marvin Anderson             | Exonerated                  | https://www.youtube.com/watch?v=_DSS18Prxmo |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_023.mp4 | Defendant / Alan Newton                 | Exonerated                  | https://www.youtube.com/watch?v=E2PpqxrFBpo |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_024.mp4 | Defendant / Ken Wyniemko                | Exonerated                  | https://www.youtube.com/watch?v=B_sQAlIIYiM |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_025.mp4 | Defendant / Ken Wyniemko                | Exonerated                  | https://www.youtube.com/watch?v=B_sQAlIIYiM |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_026.mp4 | Defendant / Mitchelle Blair             | Guilty                      | https://www.youtube.com/watch?v=PEJfPLK5YsY |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_027.mp4 | Prosecutor Witness / Martin Macneill    | Guilty                      | https://www.youtube.com/watch?v=O467AXiC-4I |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_028.mp4 | Witness / Donna Scrivo                  | Guilty                      | https://www.youtube.com/watch?v=WfS3TlHzIjw |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_029.mp4 | Witness / Bessman Okafor                | Guilty                      | https://www.youtube.com/watch?v=pSthDg5pF9M |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_030.mp4 | Witness / James Boyd                    | Officer charged with murder | https://www.youtube.com/watch?v=zWZNfycJWtM |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_031.mp4 | Witness / Bessman Okafor                | Guilty                      | https://www.youtube.com/watch?v=pSthDg5pF9M |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_032.mp4 | Witness / Bessman Okafor                | Guilty                      | https://www.youtube.com/watch?v=pSthDg5pF9M |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_033.mp4 | Witness / Bessman Okafor                | Guilty                      | https://www.youtube.com/watch?v=pSthDg5pF9M |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_034.mp4 | Witness / Bessman Okafor                | Guilty                      | https://www.youtube.com/watch?v=pSthDg5pF9M |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_035.mp4 | Witness / Bessman Okafor                | Guilty                      | https://www.youtube.com/watch?v=rorTrZ9FGQ0 |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_036.mp4 | Witness / Bessman Okafor                | Guilty                      | https://www.youtube.com/watch?v=rorTrZ9FGQ0 |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_037.mp4 | Witness / Jonathan Santillan            | Guilty                      | https://www.youtube.com/watch?v=QeCGOCUBCFk |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_038.mp4 | Witness / Bessman Okafor                | Guilty                      | https://www.youtube.com/watch?v=B4CzIRwbkIU |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_039.mp4 | Witness / Jamie Hood                    | Guilty                      | https://www.youtube.com/watch?v=SsLVmhaUWM4 |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_040.mp4 | Witness / Jamie Hood                    | Guilty                      | https://www.youtube.com/watch?v=hQ1KE1E5Hg0 |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_041.mp4 | Defendant / James Boyd                  | Officer charged with murder | https://www.youtube.com/watch?v=1FAB5bE8Jqg |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_042.mp4 | Witness / James Boyd                    | Officer charged with murder | https://www.youtube.com/watch?v=zHyqIG5xASc |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_043.mp4 | Witness / James Boyd                    | Officer charged with murder | https://www.youtube.com/watch?v=D57ybzTYOpQ |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_044.mp4 | Witness / Charles and Kimberly Matthews | Not Guilty                  | https://www.youtube.com/watch?v=Z3OHdiUgIsY |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_045.mp4 | Witness / Charles and Kimberly Matthews | Not Guilty                  | https://www.youtube.com/watch?v=Z3OHdiUgIsY |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_046.mp4 | Witness / Charles and Kimberly Matthews | Not Guilty                  | https://www.youtube.com/watch?v=Z3OHdiUgIsY |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_047.mp4 | Witness / Charles and Kimberly Matthews | Not Guilty                  | https://www.youtube.com/watch?v=yvrmul6o06c |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_048.mp4 | Witness / Charles and Kimberly Matthews | Not Guilty                  | https://www.youtube.com/watch?v=yvrmul6o06c |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_049.mp4 | Witness /  Mitchelle Blair              | Guilty                      | https://www.youtube.com/watch?v=Pils_MUrybI |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_050.mp4 | Witness / Carlos Riley                  | Not Guilty                  | https://www.youtube.com/watch?v=C6EA57XPQS0 |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_051.mp4 | Victim / Owen Labrie                    | Guilty                      | https://www.youtube.com/watch?v=1d05WATyLY8 |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_052.mp4 | Witness / Edgar Collazo                 | Guilty                      | https://www.youtube.com/watch?v=tfPqy_CpYy4 |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_053.mp4 | Defendant / Crystal Mangum              | Guilty                      | https://www.youtube.com/watch?v=t3nuzZR6tUw |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_054.mp4 | Defendant / Jodi Arias                  | Guilty                      | https://www.youtube.com/watch?v=AFIfLA0LmbM |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_055.mp4 | Defendant / Jodi Arias                  | Guilty                      | https://www.youtube.com/watch?v=AFIfLA0LmbM |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_056.mp4 | Defendant / Jodi Arias                  | Guilty                      | https://www.youtube.com/watch?v=AFIfLA0LmbM |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_057.mp4 | Defendant / Amanda Hayes                | Guilty                      | https://www.youtube.com/watch?v=q98xXFR2Q28 |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_058.mp4 | Defendant / Amanda Hayes                | Guilty                      | https://www.youtube.com/watch?v=q98xXFR2Q28 |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_059.mp4 | Defendant / Amanda Hayes                | Guilty                      | https://www.youtube.com/watch?v=q98xXFR2Q28 |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
| trial_truth_060.mp4 | Defendant / Crystal Mangum              | Guilty                      | https://www.youtube.com/watch?v=t3nuzZR6tUw |
+---------------------+-----------------------------------------+-----------------------------+---------------------------------------------+
-----------------------------------------------------------------
5. Transcripts and Annotations

Transcriptions of the videoclips were collected using Mechanical Turk. Transcribers included word repetitions and fillers such as um, ah, and uh, and also indicated intentional silence using ellipsis. Obtained transcriptions were manually verified to avoid spam and ensure their quality. 

The gesture annotations were performed using the MUMIN coding scheme (Allwood, Jens, et al. "The MUMIN multimodal coding scheme." NorFA yearbook 2005 (2005): 129-157.). Nine gesture categories consisting of facial displays and hand gestures were annotated following MUMIN's guidelines. Gestures in each categoy are listed below:

-General face:
Smile 
Laughter 
Scowl 
Other

-Eyebrows:
Frowning
Raising
Other

-Eyes: 
Exaggerated Opening 
Closing-both 
Closing-one 
Closing-repeated
Other

-Gaze :
Towards interlocutor
Up 
Down 
Sideways 
Other

-Mouth Openness: 
Open mouth
Closed mouth

-Mouth Lips: 
Corners up 
Corners down
Protruded 
Retracted

-Head Movements:
Single Nod (Down) 
Repeated Nods (Down) 
Move Forward 
Move Backward 
Single Tilt (Sideways) 
Repeated Tilts (Sideways) 
Side-turn 
Shake (repeated) 
Waggle 
Other

-Hand Movements:
Both-H both hands
Single-H single hand
Other

-Hands Trajectory:
Up
Down 
Sideways 
Complex
Other

-----------------------------------------------------------------
6. Feedback
For further questions or inquiries about this dataset, you can contact: Veronica Perez-Rosas, Mohamed Abouelenien, Rada Mihalcea, and Mihai Burzo
vrncapr@umich.edu
zmohamed@umich.edu
mihalcea@umich.edu
mburzo@umich.edu

-----------------------------------------------------------------
7. Citation Information
Bibtex:
@inproceedings{Perez-Rosas:2015:DDU:2818346.2820758,
author = {P{\'e}rez-Rosas, Ver\'{o}nica and Abouelenien, Mohamed and Mihalcea, Rada and Burzo, Mihai},
title = {Deception Detection Using Real-life Trial Data},
booktitle = {Proceedings of the 2015 ACM on International Conference on Multimodal Interaction},
series = {ICMI '15},
year = {2015},
isbn = {978-1-4503-3912-4},
location = {Seattle, Washington, USA},
pages = {59--66},
numpages = {8},
url = {http://doi.acm.org/10.1145/2818346.2820758},
doi = {10.1145/2818346.2820758},
acmid = {2820758},
publisher = {ACM},
address = {New York, NY, USA},
keywords = {deception detection, multimodal, non-verbal, real-life trial, verbal},
} 

Text:
Veronica Perez-Rosas, Mohamed Abouelenien, Rada Mihalcea, and Mihai Burzo. 2015. Deception Detection using Real-life Trial Data. In Proceedings of the 2015 ACM on International Conference on Multimodal Interaction (ICMI '15). ACM, New York, NY, USA, 59-66. 

-----------------------------------------------------------------
8. Acknowledgements
This material is based in part upon work supported by National Science Foundation awards #1344257 and #1355633, by grant #48503 from the John Templeton Foundation, and by DARPA-BAA-12-47 DEFT grant #12475008. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the authors and do not necessarily reflect the views of the National Science Foundation, the John Templeton Foundation, or the Defense Advanced Research Projects Agency.

