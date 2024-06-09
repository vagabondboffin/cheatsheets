# Command Line Cheatsheet for Virtual Environments in Python
## Basic Commands:
- Install `virtualenv`:
```
pip install virtualenv
```
- Create a virtual environment:
```
virtualenv myEnv
```
- Activate your environment:
```
.\myEnv\Scripts\activate
```
- Output installed packages in requirements format:
```
pip freeze --local > requirements.txt
type requirements.txt
```
- To deactivate the venv:
```
deactivate
```
- To delete the venv, you need to delete the directory and all of its subdirectories:
```
rmdir habitTracker_env /s
```
- We can use the `requirements.txt` file to create anther venv with the same packages:
```
virtualenv myEnv2
.\myEnv2\Scripts\activate
pip install -r requirements.txt
```
