## Hi, I'm Dayanara


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


## Get in touch

- Twitter: https://twitter.com/dayanara846
- Personal Site: dayanara846.github.io

## Latest Posts (Spanish)

{% for post in latest_post %}
- [{{post.title}}]({{post.link}})
{%  endfor %}
