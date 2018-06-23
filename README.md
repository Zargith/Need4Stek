#Need4Stek
Autonomous car which must be capable of driving on a track without hitting the walls or driving in the wrong direction.

Projet that permited to drive a simulated car

You need to use to use the software V-REP for using this project.
You would find a directory with scenes for V-REP. You just need after to drag and drop them in the software when it's launch.

To use this project you also need to compile it with command: make

Then a binary named "ai" will apear.

After that you need to execute the following command with V-REP launched to start the simulation: ./pipe.sh

If you want to launch the existing unit tests, you must use the folling command: make tests_run
To clean them, you must use the following command: make tests_fclean