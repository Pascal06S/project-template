# Setup of a template project

This guide provides a short explanation how to setup and use the cookiecutter template with [uv](https://docs.astral.sh/uv/). It follows the kedro structure and pre-installs vital dependencies needed in most projects.

### 1) Install uv

Follow the installation guide provided [here](https://docs.astral.sh/uv/getting-started/installation/) or simply execute one of the following commands corresponding to your OS:

*Windows*
`powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"`

*Linux*
`curl -LsSf https://astral.sh/uv/install.sh | sh`

---

### 2) Clone template with cookiecutter

Change to your desired workspace and run either one of the following commands in your console to clone the template with cookiecutter as general tool in uv.

`uv tool run cookiecutter [LINK]` or `uvx cookiecutter [LINK]`

You will be asked to fill out basic information about your project, including name, description and python version (default available).
After you entered the information, your custom project folder should have been created in your current directory.

---

### 3) Sync dependencies

Change directory to your newly created folder with

`cd [project_name]`

To install all pre-defined dependencies (pandas, numpy, kedro, ...) run the following command **within your newly created folder**.

`uv sync`

This command automatically creates a venv in `./venv`.

---

### 4) Running your project

You can choose between two different methods of running your project.

**A) Activate virtualenv**
`.venv\Scripts\activate` for Windows 
`source .venv/Scripts/activate` for Linux/MacOS.

Now you can run your commands as usual within the created and activated virtualenv.

**B) Run with uv**
Alternatively, running your commands with prefix `uv run` automatically runs them within the created venv.
(*Example:* `uv run which python`)

---

### 5) Dependency management
Dependencies can be easily installed and removed using uv. Run the following commands from either within or outside the venv *(when outside, keep in mind to run them within the project folder)*.

`uv add [dependency]` or `uv remove [dependency]`