## Hi, I'm Rafnix
![](https://raw.githubusercontent.com/rafnixg/rafnixg/master/rafnix_header.jpeg)

![Python application](https://github.com/rafnixg/rafnixg/workflows/Python%20application/badge.svg?branch=master&event=schedule) ![Visitors](https://visitor-badge.laobi.icu/badge?page_id=rafnixg.rafnixg)

```python
class RafnixG:

    def __init__(self):
        self.username = 'dayanara846'
        self.name = 'Dayanara M. Diaz Vargas'
        self.web = 'dayanara846.github.io'
        self.twitter = '@dayanara846'
        self.code = {
            'data analysis': ['R', 'Python', 'C++', 'STATA', 'Eviews', 'Excel', 'JavaScript'],
            'visualization': ['Tableau', 'Microsoft PowerBI', 'ArcGIS'],
            'database': ['SQL', 'Microsoft Access'],
            'Web Apps': ['Shiny', 'Plotly', 'Spyre'],
            'tools': ['GIT', 'GitHub', 'GitLab', 'Jupyter notebook', 'Pandas'],
            'favorite libraries': ['TensorFlow', 'Keras', 'PyTorch', 'Scipy', 'Quantmod', 'Quandl', 'Ggplot2', 'Dplyr', ''],
            'misc': ['Firebase', 'TDD', 'SCRUM', 'SOLID', 'GNU/Linux']
        }
        self.architecture = ['SPA', 'MVC', 'Serverless', 'microservices']

    def __str__(self):
        return self.name


if __name__ == '__main__':
    me = RafnixG()


```

[![Summary widget](https://cr-ss-service.azurewebsites.net/api/ScreenShot?widget=summary&username=rafnixg&show-header=true)](https://profile.codersrank.io/user/rafnixg)
## Get in touch

- Twitter: https://twitter.com/rafnixg
- Personal Site: https://rafnixg.dev

## Latest Posts (Spanish)

{% for post in latest_post %}
- [{{post.title}}]({{post.link}})
{%  endfor %}
