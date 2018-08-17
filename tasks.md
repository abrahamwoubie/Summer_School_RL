---
layout: default
title: Tasks | UEF Summer School 2018
---

{% include buttons.html %}


## Learning diary
Returnables: Filled learning diary (Deadline 9.9) <br>
Filled learning diary will be returned to Moodle ([https://moodle.uef.fi/course/view.php?id=17032](https://moodle.uef.fi/course/view.php?id=17032)).

For the first week of the course, participants are required to submit filled
learning diary that consists of different questions related to given lectures.

**Learning diary questions:** [https://moodle.uef.fi/mod/resource/view.php?id=1309620](https://moodle.uef.fi/mod/resource/view.php?id=1309620)


## Project (done during second week, 20.8 - 24.8, and onward)
Returnables: Final report and source code (Deadline 9.9) <br>
Report and source code will be returned to the Moodle.


#### Challenge 1: Train an agent that plays Toribash
- Toribash is a 1v1 fighting game.
- Design and/or train an agent for Toribash-DestroyUke-v1 task: The higher cumulative reward at the end of the game/episode, the better. Find the environment from Github link below.
- Ready made learning environment (ToriLLE) can be found from this link:
[https://github.com/Miffyli/ToriLLE](https://github.com/Miffyli/ToriLLE)
- Information about ToriLLE can be found from our paper
[https://arxiv.org/abs/1807.10110](https://arxiv.org/abs/1807.10110)

#### Challenge 2: Imitating a celebrity voice
- Use the corpus VoxCeleb ([http://www.robots.ox.ac.uk/~vgg/data/voxceleb/](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/))
- It contains a very large number (> 1000) of celebrity voices. Find closest to
your voice using speaker recognition technology.
- Try to see if you can get better score by modifying your voice.
- Get the project package including pre-trained speaker recognition models from [here](http://cs.uef.fi/~vvestman/files/celeb_match_project.zip).

#### Challenge 3: Test the impact of environmental noise in a Speaker Recognition System (SRS)
- Modify a set of speech signals from Voxceleb by adding noise and test the performance of the SRS (Use the SRS from the practice)
- Apply a speech enhancement method and recheck the system performance (e.g. Wiener filter in Scipy)
- Challenge the system with a different issue and compare results (e.g. short duration)
- Record your own voice and repeat the process. Compare the obtained results with the one with the previous set of signals and discuss.
- Get the project package including pre-trained speaker recognition models from [here](http://cs.uef.fi/~vvestman/files/challenge3.zip).
