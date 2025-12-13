# AccuKnox-user-management-tests

Automated E2E tests for OrangeHRM User Management module using Playwright (Python).

## Author
Nitz Mohan  
GitHub: [Nitz44](https://github.com/Nitz44)

## Playwright version
playwright==1.57.0

## Prerequisites
- Python 3.8+ (3.10 recommended)
- pip
- Git

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/Nitz44/AccuKnox-user-management-tests.git

   cd AccuKnox-user-management-tests

## Create a virtual environment and activate
python3 -m venv .venv
source .venv/bin/activate

## Install dependencies
pip install -r requirements.txt

## Install Playwright browsers
python -m playwright install


## Run test
pytest -q tests/test_01_add_user.py -s
pytest -q tests
