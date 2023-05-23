# pythonenvsetup
set up python3 dev environment on macos

Save the script to a file, for example, setup_python_dev_environment.sh. Then, open the Terminal, navigate to the directory where you saved the script, and run the following command to make it executable:

```bash
bash
```

```bash
chmod +x setup_python_dev_environment.sh
```
Finally, execute the script with the following command:

```bash
bash
```
```bash
./setup_python_dev_environment.sh
```
The script will check if Homebrew is installed and install it if necessary. Then it updates Homebrew, installs Python 3, pipenv, and adds pipenv to the PATH. It verifies the Python installation and completes the setup by displaying a message.

You can customize the script by uncommenting the relevant lines and adding any additional Python packages you need for your development environment.
