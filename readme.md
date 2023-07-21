1. Install a virtual env.
    pip install python3-venv
    or
    sudo apt install python3-venv

2. Create a virtual env
    python3 -m venv .venv

3. Activate the virtual env
    . .venv/bin/activate  **on linux**

4. Install the requirements.txt
    pip install -r requirements.txt

5. To automatically generate a requirements.txt file
    pip freeze > requirements.txt