# pi-art
![GitHub repo size](https://img.shields.io/github/repo-size/sbenstewart/pi-art)

Get the pixel form of the digits of pi as a wallpaper using either the number of digits of pi you want or the screen resolution.<br>

## Prerequisites

Before you begin, ensure you have met the following requirements:
* You have installed the latest version of [Python3](https://www.python.org/downloads/)
* You have the [pip](https://pip.pypa.io/en/stable/installing/) package manager.

* You have the [jupyter notebook](https://github.com/jupyter/notebook/blob/master/README.md#installation) installed.

* Microsoft Visual Studio 2019 Build Tools (https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2017) and add to Environment Variable (Control Panel> System and Security> System> Advanced System Settings> Advanced> Environment Variables> Path) and add the path of the folder containing the cl.exe file (in this system, it's at C:\Program Files (x86)\Microsoft Visual Studio\2019\BuildTools\VC\Tools\MSVC\14.24.28314\bin\Hostx64\x86\).
* For gmpy2 installation in Windows 10, download the pre-compiled binary file (gmpy2-2.0.8-cp36-cp36m-win_amd64.whl from https://www.lfd.uci.edu/~gohlke/pythonlibs/#gmpy ) 
Then run 
```
pip install gmpy2-2.0.8-cp36-cp36m-win_amd64.whl 
```

If the above are too complicated you can use the Python3 version of [Anaconda](https://www.anaconda.com/distribution/) which serves the same purpose. But requires a bit more of processing power and storage to install.

## Using pi-art

To get started with pi-art, follow these steps:

* Clone the repository to your local machine.
* Change to the repo directory.
* Run the following command to install the required packages.
```
pip install -r requirements.txt
```
* Start the jupyter notebook.
```
jupyter notebook
```
* It opens up the web browser. 
* Navigate to the repo directory.
* You will find two files.
    1. code.ipynb
    2. square.ipynb

## Run using digits of pi
For this, you will have to open the `square.ipynb` file in the jupyter webpage.

Now change the value of the `number_of_digits` variable in the notebook. 

Once it is changed, run the whole notebook.

The output will be a `square image of pi` with the maximum possible digits of the given value in the `number_of_digits` crammed into it.

## Run using screen resolution
For this, you will have to open the `code.ipynb` file in the jupyter webpage.

Now change the value of the `width` and `height` variables in the notebook. 

Once it is changed, run the whole notebook.

The output will be an `image of pi` for the resolution specified.

## Output

The output of the notebook will be stored in the file named `pi-art.png` in the same folder.

![The photo](pi-art.png?raw=true "Pi-art")

## Contributing to pi-art
To contribute to pi-art, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <user_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

## Contact

If you want to contact me you can reach me at <sbenstewart@gmail.com>.

**Have a great day :)**
