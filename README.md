# Hello there it's Lahcene Nouali 😁
 
 
```python 
from django.views.generic.detail import DetailView

class AboutMe(DetailView):
  name = "Lahcene Nouali"
  location = "Tlemcen, ALgeria"
  education = "Computer Science & Artificial Intelligence"
  website = "lahcene13.github.io"
  
   #get social media links
  def get_social_contact(self)
    social_media_links = {
      "linkedin" : "linkedin.com/in/nouali"
      "twitter": "twitter.com/lahcene_nouali"
      "stackoverflow" : "stackoverflow.com/users/13082964/lahcene"
    }    
    return social_media_links 
  
  #get all my favourite  programming languages
  def get_fav_lang(self):
      languages = ['python🐍 ', 'javascript😺 ', 'c++☕']
      return languages
      
  #get all my favourite frameworks
  def get_fav_frameworks(self):
    frameworks = ['django🔫 ', 'react🎯', 'bootstrap✨ ', 'django-rest-framework🧬 ']
    return frameworks
   
  #get all my favourite databases 
  def get_databases(self)
   data_bases = ['postgres🐘 ', 'mysql👍', 'mongodb🍃']
   return data_bases
