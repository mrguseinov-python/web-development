### Installation

Update the software.
```
sudo apt update && sudo apt upgrade -y
```

Install python and pip (python package manager).
```
sudo apt install python3.8 python3-pip
```

Install virtualenv (python environments manager).
```
pip3 install virtualenv && source ~/.profile
```

Clone the repository and cd into it.
```
git clone https://github.com/mrguseinov-python/web-development.git && cd web-development
```

Create a new virtual environment and activate it.
```
virtualenv venv && source venv/bin/activate
```

Install the required packages.
```
pip install -r requirements.txt
```

---

### Usage

Activate the virtual environment if it's not active.
```
source venv/bin/activate
```

Start the development server.
```
flask run
```
