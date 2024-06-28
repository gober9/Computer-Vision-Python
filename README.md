# Computer-Vision-Python
## Lab Requirements 

To do this lab, make sure to have Python and Visual Studio installed. We will be installing opencv-python, numpy, imutils, dlib, and scipy from the terminal/command prompt or in a virtual environment. 

### Installing Required Packages Option 1
Open the Terminal/Command prompt and install the required packages globally on your device. 

'''sh
pip install opencv-python numpy imutils dlib scipy
'''

### Installing Required Packages Option 2
1. Create a virtual environment in your terminal/command prompt.

'''sh
python -m venv myenv
'''

2. Activate the virtual environment 
- On Windows:
'''sh
myenv\Scripts\activate
'''

- On macOS/Linux:
'''sh
source myenv/bin/activate
'''

3. Install the packages within the virtual environment:

'''sh
pip install opencv-python numpy imutils dlib scipy
'''

### Set Up Visual Studio
1. Open Visual Studio 
Create a new project or open an existing one.
- To create a new project, go to File > New > Project..., select Python from the project templates, and follow the prompts to set up your project.

2. Configure the Python Environment 
- In the 'Options' window, navigate to 'Python > Environments'.
    - If you are downloaded it to your own device, you should see it appear in Global.
    - If you are using a virtual environment, select 'Existing environment' and select the 'venv'. 

3. Add Your Packages to the Project
- Click on "Python > Packages' and ensure the installed packages are listed 
- If they are not listed, you can manually add them by specifying the package names. 
    - For example, you can type 'opencv-python' in search box and install it. 

4. Verify the Installation 
- Create a new python file called 'verify_installation.py' and add the following script

'''python
import cv2
import numpy as np
import imutils
import dlib
import scipy

print("Packages imported successfully!")
'''

- Run the script and ensure this message is displayed in the terminal "Packages imported successfully!"