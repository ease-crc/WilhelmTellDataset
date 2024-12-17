# The Wilhelm Tell Dataset of Affordance Demonstrations

The Wilhelm Tell Dataset is a novel dataset for affordance learning of common household tasks. Our dataset consists of video sequences demonstrating tasks from first- and third-person perspectives, along with metadata about the affordances that are manifested in the task, and is aimed towards training perception systems to recognize affordance manifestations.  The demonstrations were collected from 23 participants and in total record about seven hours of human activity.

## Data collection methodology

Participants were asked to stand in front of a table with a variety of household objects and instructed to perform various small tasks centered around apples, using the objects
to demonstrate affordances. The tasks were filmed from the ego perspective using a GoPro headset camera and from the frontal perspective using a stationary camera on a tripod.

[Add affordance tables from the paper here]

The data was collected in three sessions. In the first sessionceight participants were asked to complete 14 tasks in two bundles of 7 as shown in Table I. Task 3 and 4 were varied with the a option used in the first round and the b option used in the second round of the study. The tools used were switched after the first 7 tasks to provide more variety in the recordings and the apple was replaced with an intact one.
For the second and third recording session the list of tasks was expanded with more tasks that demonstrate additional affordances. Due to the time needed for those added tasks theywere split into four parts. During the first round participants completed tasks 8-10 in the a-variant and then continued with tasks 1-7 in the a-variant. The objects were then replaced with different variations of the same object and the participants repeated tasks 8-10 and then 1-7 in the b-variant. Afterwards the objects on the table were replaced with different objects and the participants received instructions for tasks 11-20 in the a-variant. Following this, the objects were again replaced with different variations, and participants then instructed to
complete tasks 11-20 in the b-variant.

### Description of the data

The data is split into folders by participant id. Each participant folder contains the ego and frontal perspective videos in mp4 format for each bundle of tasks as well as a video containing all task bundles in one.

```
WilhelmTellDataset/
  -P1/
    -P1_Ego_1.mp4
    -P1_Ego_2.mp4
    -...
    -P1_Ego_Complete.mp4
    -P1_Frontal_1.mp4
    -P1_Frontal_2.mp4
    -...
    -P1_Frontal_Complete.mp4
    -...
  -P2/
    -P2_Ego_1.mp4
    -P2_Ego_2.mp4
    -...
    -P2_Ego_Complete.mp4
    -P2_Frontal_1.mp4
    -P2_Frontal_2.mp4
    -...
    -P2_Frontal_Complete.mp4
    -...   
  -...
  -README.md
  -LICENSE.md

```

### File formats

- 189 videos in MP4 format with a total of 445 minutes of material

## Download link

* [Wilhelm Tell Dataset Repository](https://nc.uni-bremen.de/index.php/s/3prZnQBz7pL8M2i) - Link to the dataset videos hosted on university servers.

## Related publications

[Link]() and Bibtex for HRI paper here

## Authors

* **Rachel Ringe** - rringe@uni-bremen.de 
* **Mihai Hawkin** - mpomarlan@uni-bremen.de
* **Nikolaos Tsiogkas** - nikolaos.tsiogkas@kuleuven.be
* **Stefano De Giorgis** - stefano.degiorgis2@unibo.it
* **Maria Hedblom** - maria.hedblom@ju.se
* **Rainer Malaka** - malaka@tzi.de

## License

This project is licensed under the CC-BY license - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* [Project Acknowledgements here]
