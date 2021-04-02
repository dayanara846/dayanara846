## Hi, I'm Dayanara
![](https://giphy.com/gifs/caitlinburns-glitch-finance-stock-market-l41lZBP84rdzHnWA8)




```python
class Dayanara846:

    def __init__(self):
        self.username = 'dayanara846'
        self.name = 'Dayanara M. Diaz Vargas'
        self.web = 'dayanara846.github.io'
        self.linkedin = 'https://www.linkedin.com/in/dayanara-mary-diaz-vargas/'
        self.twitter = '@dayanara846'
        self.code = {
            'data analysis': ['R', 'Python', 'C++', 'STATA', 'Eviews', 'Excel'],
            'visualization': ['Tableau', 'Microsoft PowerBI', 'ArcGIS'],
            'database': ['SQL', 'Microsoft Access'],
            'Web Apps': ['Shiny', 'Plotly', 'Spyre'],
            'Front-End Web Development': ['HTML', 'CSS', 'JavaScript', 'JSON']
            'tools': ['GIT', 'GitHub', 'GitLab', 'Jupyter notebook', 'Pandas'],
            'favorite libraries': ['TensorFlow', 'Keras', 'PyTorch', 'Scipy', 'Quantmod', 'Quandl', 'Ggplot2', 'Dplyr']
        }
        self.interests = ['judo', 'finance', 'social sciences', 'data science', 'Ariana Grande']

    def __str__(self):
        return self.name


if __name__ == '__main__':
    me = Dayanara846()


```


## Get in touch

- Twitter: https://twitter.com/dayanara846
- Personal Site: https://dayanara846.github.io/#/

## Latest Posts (Spanish)

{% for post in latest_post %}
- [{{post.title}}]({{post.link}})
{%  endfor %}
