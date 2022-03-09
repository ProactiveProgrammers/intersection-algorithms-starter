# Intersection Algorithms

## Assigned: Wednesday, March 9, 2022
## Due: Wednesday, March 16, 2022

After cloning this repository to your computer, please take the following steps:

- Follow the instructions on the Proactive Programmers web site for this project
- Use the `cd` command to change into the directory for this repository
- Change into the program directory by typing `cd intersection`
- Install the dependencies for the project by typing `poetry install`
- Run the program in with both algorithms by typing:
  - `poetry run intersection --number 1000 --maximum 25 --profile --approach TupleSingle`
  - `poetry run intersection --number 1000 --maximum 25 --profile --approach TupleDouble`
  - `poetry run intersection --number 1000 --maximum 25 --profile --approach ListSingle`
  - `poetry run intersection --number 1000 --maximum 25 --profile --approach ListDouble`
  - Please note that these are not the only configurations you should try for your experiment
  - Please note that the program will not work unless you add the required source code
  - Please refer to the `writing/reflection.md` file for all ways to run the program
  - You should regularly commit to your GitHub repository and write meaningful commit messages
- Confirm that the program is producing the expected output
- Use a `docker run` command for your operating system to run GatorGrader
- Please be aware that performance profiling in a Docker contain may not work as expected
- Provide all of the required responses in the `writing/reflection.md` file
