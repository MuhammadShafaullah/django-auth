# django-auth
#  End points
# 1. Register User
# URL   localhost:8000/api/register
{
    "name": "testuser",
    "email": "tanni@.com",
    "password": "pak12345"

}

# 1. Login
# URL   localhost:8000/api/login
{
    "email": "tanni@.com",
    "password": "pak12345"
}

# 2. Get User
# URL   localhost:8000/api/user
# get user details by token that stored in cookie

# 3. logout
# URL   localhost:8000/api/logout
# logout user by token that stored in cookie



# Facing issue in creating superuser
# python manage.py createsuperuser



# working on endpoint to update password or user

