# MyWhoosh to Garmin Sync Activities

A script that automates synchronization of activites from MyWhoosh to Garmin Connect.

## Installation and Setup

### Clone the repository
```bash
git clone https://github.com/mvace/mywhoosh_to_garmin.git
```

### Navigate to project folder
```bash
cd .\mywhoosh_to_garmin\
```

### Create virtual environment
```bash
python -m venv .venv
```

### Activate virtual environment
```bash
.\.venv\Scripts\activate
```

### Install dependencies
```bash
pip install -r requirements.txt
```

### Configure environment variables
1. Rename `.env.example` to `.env`
2. Open `.env` file and fill in your credentials:
  - MYWHOOSH_EMAIL: Your MyWhoosh account email
  - MYWHOOSH_PASSWORD: Your MyWhoosh account password
  - GARMIN_EMAIL: Your Garmin Connect email
  - GARMIN_PASSWORD: Your Garmin Connect password

### Run the script
```bash
python main.py
```


## Prerequisites

* Python (I used Python 3.11.)
* Git

