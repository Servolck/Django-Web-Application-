# Django-Web-Application-
Creates a basic web application using the Django framework.
from django.http import HttpResponse
from django.urls import path
from django.shortcuts import render

def home(request):
    return HttpResponse("Hello, Django!")

urlpatterns = [
    path('', home, name='home'),
]
