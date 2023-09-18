# Flexi-Blender

Flexi-Blender is a Python script that facilitates the integration of 3D matrix data from a CSV file to animate a character within a Blender environment. It's an essential tool for animators and Blender enthusiasts looking for an efficient way to incorporate complex data structures into their projects.

## Getting Started

To get started, you'll first need to set up your environment correctly and ensure you have the necessary dependencies installed.

### Prerequisites

Before you begin, make sure you have [Blender](https://www.blender.org/download/) installed on your system.

### Installation

1. Clone the repository to your local machine.

git clone https://github.com/flexitrace/flexi-blender.git

python


2. Open the Blender application and load the `model.blend` file from the cloned repository.

3. Before running the main script, execute the `setup_env.py` script within Blender to install the required `pandas` package. You can do this by opening the script in Blender's text editor and running the script (or by using the built-in Python console).
```python
import pip
pip.main(['install','pandas~=2.1.0'])

Usage

Once the environment is set up, you can use the csv_to_animation.py script to animate your character with the 3D matrix data from the sample.csv file. Here's how to use the script:

    Load the csv_to_animation.py script in Blender's text editor.
    Run the script. This script reads data from the sample.csv file and uses it to animate the character in the model.blend file.

Script Details

Here's a brief explanation of the main components of the csv_to_animation.py script:

    LOC_OR_GLOB: Specifies whether the transformations are in local or global coordinates.
    OBJECT_NAME: The name of the object to be animated.
    ARMATURE_NAME: The name of the armature controlling the object.
    CSV_FILE: The path to the CSV file containing the animation data.
    MATRIX_LOC_OR_GLOB: Specifies which coordinate system (local or global) to use from the LOC_OR_GLOB list.

Function

    csv_to_animation2(obj, arm, csv_file, loc_or_glob): This function takes the object name, armature name, CSV file path, and coordinate system as arguments, and animates the character based on the data in the CSV file.

Contributing

We welcome contributions to the Flexi-Blender project! Please feel free to open an issue or create a pull request with your improvements or suggestions.
License

This project is open-source and available under the MIT License.
Contact

If you have any questions or feedback, please open an issue on GitHub, and we will get back to you as soon as possible.

css


Please, adjust any sections as necessary to better suit your project’s needs and details. You might also
