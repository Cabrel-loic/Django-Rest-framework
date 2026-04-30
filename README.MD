# Django REST Authentication Example

Thanks for checking out this project! This is a simple Django REST authentication system built quickly as a learning example. It is designed to be easy to run locally and modify for your own needs.

## What this project includes

- Custom Django user model
- Sign up and login endpoints
- JWT authentication using `djangorestframework-simplejwt`
- CORS support via `django-cors-headers`

## Prerequisites

Make sure you have the following installed:

- Python 3.12 or higher
- Node.js 20+
- npm or yarn

> If you are on macOS or Linux, use the shell commands shown in the Mac/Linux section below.

## Clone this repository

```bash
git clone https://github.com/Cabrel-loic/Django-Rest-framework.git
cd Django-Rest-framework
```

## Setup on Windows

### Create and activate a virtual environment

```powershell
python -m venv venv
venv\Scripts\activate
```

### Install dependencies

```powershell
uv add django djangorestframework djangorestframework-simplejwt python-dotenv django-cors-headers django-filter pillow
```

## Setup on macOS / Linux

### Create and activate a virtual environment

```bash
python3 -m venv venv
source venv/bin/activate
```

### Install dependencies

```bash
uv add django djangorestframework djangorestframework-simplejwt python-dotenv django-cors-headers django-filter pillow
```

## Run the project

```bash
python manage.py runserver
```

Then open your browser at:

```text
http://localhost:8000/signup/
```

## Notes

- If you are using macOS/Linux, prefer `python3` where available.
- Activate the virtual environment before running install or server commands.
- This repository is a starting point; feel free to improve authentication, add email verification, or strengthen security.

## Recommended next steps

- Add token refresh and blacklist handling
- Implement password reset and email verification
- Harden password validation
- Add tests for authentication workflows
