
app = dash.Dash(__name__,  requests_pathname_prefix='/my-app/')
#app.config.requests_pathname_prefix = '' 


1. Removed server = Flask(__name__)
2. requests_pathname_prefix='/my-app/'
3. Removed:
    @server.route('/')
    def myDashApp():
       return app
