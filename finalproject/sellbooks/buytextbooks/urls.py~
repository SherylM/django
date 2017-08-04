from django.conf.urls import url
from . import views

app_name = "books"

urlpatterns = [
    #/buytextbooks/
    url(r'^$', views.home, name='home'),#views.index,name = 'index'

    #/buytextbooks/3(id)/
    url(r'^(?P<book_id>[0-9]+)/$', views.detail, name = 'detail'),

    #/buytextbooks/index.html/
    url(r'^index.html/', views.index, name='index'),


]
