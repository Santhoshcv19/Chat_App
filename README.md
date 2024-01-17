
# Django Chat Application

This is a chat application built using Django, Django Channels, and Daphne. It allows users to create and join multiple chat rooms, facilitating real-time communication.

## Features

- Multiple chat rooms
- Real-time messaging using Django Channels
- User authentication and authorization
- Responsive design for a seamless experience across devices


## Prerequisites

 - Python (>=3.6)
 - Django
 - Channels
 - Daphne
 - Redis (for Channels)
## Installation

Install my-project with npm

1. Clone the repository:
```bash
git clone https://github.com/Santhoshcv19/Chat_App.git
```
  

2. Install dependencies:
```bash
cd Chat_App
pip install -r requirements.txt
```

3. Apply database migrations:
```bash
python manage.py migrate
```
    
## Usage/Examples

1. Run the development server:
```bash
python manage.py runserver
```
Visit http://localhost:8000 in your browser.

2. For production, use Daphne as the ASGI server:
```bash
daphne Chat_App.asgi:application
```


## Deployment

Follow the Django and Channels deployment guides for production deployment with Daphne.

## Acknowledgements

 - [Django](https://www.djangoproject.com/)
 - [Django Channels](https://channels.readthedocs.io/en/latest/)
 - [Daphne](https://docs.djangoproject.com/en/5.0/howto/deployment/asgi/daphne/)


## Contributing

Feel free to contribute by opening issues or pull requests.


## Authors

- [Santhoshcv19](https://github.com/Santhoshcv19/)

