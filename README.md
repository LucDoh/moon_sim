Simulates the formation of the moon based on the Giant Impact Hypothesis. This was the final group project I worked on for UC Santa Cruz's Astro 119: Intro to Scientiic Computing class [https://sites.google.com/a/ucsc.edu/krumholz/teaching-and-courses/ast119_w15].

While a few of the classes were worked on collaboratively (main.py, rock.py), I worked solely with Aramis Marden on the class AraLuc_Trynewthings.py. This (poorly named) class deals with the collisions between asteroids/debris, resolving these collisions inelastically, and ensuring that momentum and mass was conserved. We used scipy spatial's KDTree to quickly determine rocks that were close enough to collide. - Luc d'Hauthuille



Below I've included Benjamin Stahl's description.
--------------------------------------------------------------------------------------------------

"This repository holds the final result of a group project I worked on with Jarred Gillette, Monique Windju, Cesar Gonzalez Renteria, Luc D'Hauthuille, and Aramis Marden at UCSC for a scientific computing class.

Our code does a simple simulation of the Giant Impact Hypothesis, which predicts that the moon was formed when a proto-planet collided with the Earth 4.5 Billion years ago, ejecting debris into orbit that would eventually collect under gravity to form the moon.

My specific contributions were to the following files:

- initial.py: generates the initial conditions of the simulation (I worked with JG on this)
- main.py: master script that controls the simulation (I worked with the entire group on this)
- mass_plot.py: plots the mass of the 'moon' as a function of time
- overlap_check.py: checks if a rock overlaps with the Earth, and removes it if it does
- plot_c.py: plots the current state of the simulation (I worked with CGR on this)
- rock.py: the main class used throughout the simulation (written by the group)"
